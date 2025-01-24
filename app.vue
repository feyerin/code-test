<template>
  <div>
    <Header/>
    <main>
      <div class="banner">
        
      </div>

      <Step/>

      <AboutUs/>

      <Campus/>
    </main>
    <footer>
      <!-- Konten footer -->
    </footer>
  </div>
</template>

<script>
  import Campus from  '~/components/campus/campus.vue'
  import Header from  '~/components/header/header.vue'
  import Step from '~/components/step/step.vue'
  import AboutUs from '~/components/aboutUs/aboutUs.vue'
  export default {
    // Konten logika layout
  }
</script>

<style lang="scss">
@use "~/assets/scss/main.scss";
</style>