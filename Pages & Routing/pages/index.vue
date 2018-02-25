<template>
  <AppContainer>
    <ol class="description">
      <li>Create two routes: /products and /products/:pid</li>
      <li>Add a button to the main page. The button should navigate (programmatically) to /products</li>
      <li>Add two links to the /products page. The links should go to /products/1 and /products/2</li>
      <li>Output the product id on the /products/:pid page</li>
    </ol>

    <AppButton @click="openProducts()">Products</AppButton>
  </AppContainer>
</template>

<script>
import AppButton from '~/components/AppButton'
import AppContainer from '~/components/AppContainer'

export default {
  components: { AppButton, AppContainer },
  methods: {
    openProducts () {
      this.$router.push('/products')
    }
  }
}
</script>

<style>
.description
{
  margin-bottom: 20px;
}
</style>
