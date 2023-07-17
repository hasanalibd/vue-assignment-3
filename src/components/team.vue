<script setup>
    import team1 from "../assets/images/team-1.jpg"
    import team2 from "../assets/images/team-2.jpg"
    import team3 from "../assets/images/team-3.jpg"
    import team4 from "../assets/images/team-4.jpg"
</script>

<template>
    <div class="container py-5" id="team">
      <div class="text-center">
          <h1>Our Team Members</h1>
          <p> 
            Following reasons show advantages of adding AppCo to your lead pages, <br> demos and checkouts evisculate interoperable imperatives rather.
          </p>
      </div>
      <div class="row my-3 ">
        <div class="col-12 col-lg-3 my-element"><img class="img-fluid rounded-circle" :src="team1" alt=""></div>
        <div class="col-12 col-lg-3 my-element"><img class="img-fluid rounded-circle" :src="team2" alt=""></div>
        <div class="col-12 col-lg-3 my-element"><img class="img-fluid rounded-circle" :src="team3" alt=""></div>
        <div class="col-12 col-lg-3 my-element"><img class="img-fluid rounded-circle" :src="team4" alt=""></div>
      </div>
    </div>
</template>

<style>
@media (max-width: 767.98px) {
      .my-element {
        padding: 20px;
      }
      .sm-center{
        text-align: center;
      }
      .footer-image{
        text-align: center;
        padding-bottom: 20px;
      }
    }
</style>