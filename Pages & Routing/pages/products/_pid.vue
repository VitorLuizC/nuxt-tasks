<template>
  <AppContainer>
    <h1>Product ID: {{ $route.params.pid }}</h1>
  </AppContainer>
</template>

<script>
import AppContainer from '~/components/AppContainer'

export default {
  components: { AppContainer }
}
</script>
