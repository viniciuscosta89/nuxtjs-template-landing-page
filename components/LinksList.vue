<template>
  <section class="bg__bege py-10 px-8 md:px-6">
    <div class="container flex flex-wrap mx-auto">
      <a
        v-for="item in items"
        :key="item"
        class="md:w-1/2 lg:w-1/4 mb-4 md:px-2 leading-snug"
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
