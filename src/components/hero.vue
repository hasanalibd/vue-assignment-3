<script setup>
    import hero from '../assets/images/mobile-app.png'
    import playicon from '../assets/images/google-play.png'
    import appleicon from '../assets/images/app-store.png'
</script>

<template>
    <!-- hero section -->
    <div class="container py-5 sm-py-5">
      <div class="row d-flex align-items-center">
        <div class="col-12 col-sm-6">
          <h1 class="display-3 fw-bold">Showcase your <br> app beautifully.</h1>
          <p class="py-3">Another cool free html css template by Colorlib Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast</p>
          
            <div class="image-container ">
              <img :src="appleicon" alt="" class="pe-3 my-2">
              <img :src="playicon" alt="" >
            </div>
        </div>
        <div class="col-12 col-sm-6 mt-4">
          <img class="img-fluid" :src="hero" alt="">
        </div>
      </div>
    </div>
</template>

<style scoped>

</style>