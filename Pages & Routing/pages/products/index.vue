<template>
  <AppContainer>
    <nuxt-link to="/products/1" class="link">Product 1</nuxt-link>
    <nuxt-link to="/products/2" class="link">Product 2</nuxt-link>
  </AppContainer>
</template>

<script>
import AppContainer from '~/components/AppContainer'

export default {
  components: { AppContainer }
}
</script>

<style>
.link
{
  margin: 20px 0;
}
</style>
