<template>
  <section class="bg__bege py-10 px-6">
    <div class="container flex flex-wrap mx-auto max-h-1/2">
      <a
        v-for="item in items"
        :key="item"
        class="lg:w-1/4 mb-4 px-8 px-4 lg:px-2 text-center lg:text-left leading-snug"
        :href="item.url"
      >
        {{ item.name }}
      </a>
    </div>
  </section>
</template>

<script>
import links from './json/links.json'

export default {
  name: 'LinksList',
  data () {
    return {
      items: links
    }
  }
}
</script>

<style lang="scss" scoped>
  .bg__bege {
    background-color: #ece9e2;
  }

  .transition-5 {
    transition: all .5s ease-in-out;
  }
</style>
