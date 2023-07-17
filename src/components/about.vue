<script setup>
import about from '../assets/images/about.svg'
</script>

<template>
    <div class="container py-5" id="about">
      <div class="row">
        <div class="col-12 col-lg-8">
          <img class="img-fluid" :src="about" alt="">
        </div>
        <div class="col-12 col-lg-4">
          <h3 class="fs-2 fw-medium mb-4">About Us</h3>
          <p>
            Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast <br><br>
            Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia.
          </p>
          <div>
            <p><img width="30px" src="../node_modules/bootstrap-icons/icons/check.svg" alt="">There live the blind texts</p>
            <p><img width="30px" src="../node_modules/bootstrap-icons/icons/check.svg" alt="">There live the blind texts</p>
            <p><img width="30px" src="../node_modules/bootstrap-icons/icons/check.svg" alt="">There live the blind texts</p>
          </div>
          <div class="row sm-center">
            <div class="col">
              <h2>59M</h2>
              <p>Members</p>
            </div>
            <div class="col">
              <h2>14</h2>
              <p>Team</p>
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<style scoped>

</style>