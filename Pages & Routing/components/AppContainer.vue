<template>
  <section class="AppContainer">
    <slot />
  </section>
</template>

<style>
.AppContainer
{
  min-height: 100vh;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  text-align: center;
}
</style>
