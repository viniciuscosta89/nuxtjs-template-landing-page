<template>
  <section
    :style="`background-image: url(${img})`"
    class="big-banner bg-center bg-cover bg-no-repeat"
  />
</template>

<script>
export default {
  name: 'BigBanner',
  props: {
    img: {
      default: 'none',
      type: String
    }
  }
}
</script>

<style lang="scss" scoped>
.big-banner {
  min-height: 300px;

  @media (min-width: 1140px) {
    min-height: 455px;
  }
}
</style>
