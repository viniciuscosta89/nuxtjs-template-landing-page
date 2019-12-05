<template>
  <section class="bg__bege py-10 px-8">
    <div class="container flex flex-wrap mx-auto">
      <div
        class="flex-grow lg:w-2/3 lg:pr-4 mb-4 lg:mb-0 text-center lg:text-left"
      >
        <!-- Google Maps -->
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3656.023643608589!2d-46.6155837850214!3d-23.603484984662057!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce5bbdef0ca875%3A0x4997b851143aa2d6!2sR.%20Acaraj%C3%A9%2C%20137%20-%20Vila%20Dom%20Pedro%20I%2C%20S%C3%A3o%20Paulo%20-%20SP%2C%2004277-040!5e0!3m2!1spt-BR!2sbr!4v1575420629531!5m2!1spt-BR!2sbr"
          width="100%"
          height="450"
          frameborder="0"
          style="border:0;"
          allowfullscreen=""
        />
      </div>

      <div class="flex-grow lg:w-1/3 lg:pl-4 mb-4 lg:mb-0">
        <h2 class="flex items-center font-bold text-2xl mb-4">
          <font-awesome-icon :icon="['fas', 'map-marker-alt']" class="inline-block mr-4 w-6" />
          <span class="inline-block">Localização</span>
        </h2>
        <address class="mb-4">
          R. Acarajé, 137 - Vila Dom Pedro I<br>
          São Paulo - SP<br>
          04277-040
        </address>

        <a
          class="flex items-center"
          href=""
          title=""
          target="_blank"
        >
          <font-awesome-icon :icon="['fas', 'desktop']" class="inline-block hover:text-gray-800 fa-2x mr-4 w-10 transition-5" />
          <span class="bg-black hover:bg-gray-800 inline-block text-white py-2 px-8 transition-5">Acesse o Site</span>
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Localization'
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
