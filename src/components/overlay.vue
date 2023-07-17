<script setup>
    import apphand from "/src/assets/images/app-hand-top.png"
</script>

<template>
    <div class="bg-image">
        <div class="container pt-5">
            <div class="row d-flex align-items-center">
              <div class="col-12 col-sm-6">
                <h1 class="text-white display-4 fw-semibold">Start Managing your Apps Business, more Faster</h1>
                <p class="text-white">Objectively deliver professional value with diverse web-readiness. Collaboratively transition wireless customer service without goal-oriented catalysts for change. Collaboratively.</p>
                <div>
                <button type="button" class="btn btn-light text-black my-2 px-4 py-2 rounded-pill me-3">Google Play</button>
                <button type="button" class="btn btn-outline-info my-2 px-4 py-2 text-white rounded-pill">App Store</button>
              </div>
              </div>
              <div class="col-12 col-sm-6">
                  <img :src="apphand" class="img-fluid" alt="">
              </div>
              
            </div>
        </div>
    </div>
    
</template>

<style scoped>
    .bg-image {
      background-image: url("../assets/images/app-hero-bg.jpg");
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center center;
      background-blend-mode: overlay;
      background-color: rgba(0, 0, 0, 0.8)
    }

</style>