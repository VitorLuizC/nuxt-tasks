<template>
  <button v-bind="$attrs" v-on="$listeners" class="AppButton">
    <slot />
  </button>
</template>

<style>
.AppButton
{
  margin-top: 20px;
  padding: 20px;
  border: 0;
  font-size: 20px;
  font-weight: 300;
  text-transform: uppercase;
  letter-spacing: 2px;
  color: #fff;
  background-color: coral;
  cursor: pointer;
}

.AppButton::first-letter
{
  font-size: 25px;
}

.AppButton:hover,
.AppButton:active
{
  background-color: rgb(247, 101, 49);
}
</style>
