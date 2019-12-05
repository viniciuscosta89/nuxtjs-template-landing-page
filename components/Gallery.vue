<template>
  <section class="gallery">
    <div class="container flex flex-wrap mx-auto py-6 px-8 lg:px-6">
      <div
        class="flex-grow lg:w-1/3 px-4 lg:px-2 mb-4 lg:mb-0 text-center lg:text-left"
      >
        <img
          class="inline-block max-w-full w-full"
          src="https://www.baressp.com.br/site_php/cursos_landing/images/extra/curso-bartender-flair-para-bares-2.jpg"
          alt=""
        >
      </div>

      <div
        class="flex-grow lg:w-1/3 lg:px-2 mb-4 lg:mb-0 text-center lg:text-left"
      >
        <img
          class="inline-block max-w-full w-full"
          src="https://www.baressp.com.br/site_php/cursos_landing/images/extra/curso-bartender-flair-para-bares-2.jpg"
          alt=""
        >
      </div>

      <div class="flex-grow lg:w-1/3 lg:px-2 text-center lg:text-left">
        <img
          class="inline-block max-w-full w-full"
          src="https://www.baressp.com.br/site_php/cursos_landing/images/extra/curso-bartender-flair-para-bares-2.jpg"
          alt=""
        >
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Gallery',
  props: {
    img1: {
      default: null,
      type: String
    },
    img2: {
      default: null,
      type: String
    },
    img3: {
      default: null,
      type: String
    }
  }
}
</script>

<style type="scss" scoped>
.gallery {
  background-color: #2c2d2d;
}
</style>
