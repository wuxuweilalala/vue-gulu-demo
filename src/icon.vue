<template>
  <svg class="g-icon" aria-hidden="true">
    <use :xlink:href="`#i-${name}`" />
  </svg>
</template>

<script>
  import './svg'
export default {
  props: ["name"]
};
</script>

<style lang="scss">
.g-icon {
  width: 1em;
  height: 1em;
  vertical-align: -0.15em;
  fill: currentColor;
  overflow: hidden;
}
.loading {
  animation: spin 1s infinite linear;
}
</style>