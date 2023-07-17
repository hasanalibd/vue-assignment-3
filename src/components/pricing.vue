<script setup>
import basic from '../assets/images/basic.svg'
import standard from '../assets/images/standard.svg'
import unlimited from '../assets/images/unlimited.svg'
</script>

<template>
    <div class="container py-5" id="pricing">
      <div class="text-center">
          <h1>Why Peoples Love App?</h1>
          <p> 
            Following reasons show advantages of adding AppCo to your lead pages, <br> demos and checkouts evisculate interoperable imperatives rather.
          </p>
        </div>
        <div class="row mx-auto flex justify-content-center">
          <div class="col-12 col-md-3 px-3 py-4 m-3 bg-light text-center border-4 rounded-4 shadow-sm custom-border-hover">
            <h5 class="fs-5 fw-medium">Basic</h5>
              <div><img :src="basic" alt="" width="50" class="py-3"></div>
              <p>5 Users access same time</p>
              <p>Integrated eCommerce</p>
              <p>Customization interface</p>
              <p>Weekly updated</p>
              <p>24/7 Phone Support</p>
              <p>Event Analytics</p>
              <h1 class="fs-1 fw-bold color-price">$29</h1>
              <button type="button" class="btn btn-outline-primary rounded-pill">Purchase now</button>
          </div>
          <div class="col-12 col-md-3 px-3 py-4 m-3 bg-light text-center border-4 rounded-4 shadow-sm custom-border">
            <h5 class="fs-5 fw-medium">Standard</h5>
              <div><img :src="standard" alt="" width="50" class="py-3"></div>
              <p>5 Users access same time</p>
              <p>Integrated eCommerce</p>
              <p>Customization interface</p>
              <p>Weekly updated</p>
              <p>24/7 Phone Support</p>
              <p>Event Analytics</p>
              <h1 class="fs-1 fw-bold color-price">$145</h1>
              <button type="button" class="btn btn-primary rounded-pill">Purchase now</button>
          </div>
          <div class="col-12 col-md-3 px-3 py-4 m-3 bg-light text-center border-4 rounded-4 shadow-sm custom-border-hover">
            <h5 class="fs-5 fw-medium">Unlimited</h5>
              <div><img :src="unlimited" alt="" width="50" class="py-3"></div>
              <p>5 Users access same time</p>
              <p>Integrated eCommerce</p>
              <p>Customization interface</p>
              <p>Weekly updated</p>
              <p>24/7 Phone Support</p>
              <p>Event Analytics</p>
              <h1 class="fs-1 fw-bold color-price">$259</h1>
              <button type="button" class="btn btn-outline-primary rounded-pill">Purchase now</button>
          </div>
        </div>
    </div>
</template>

<style scoped>
    .hover-backgrund:hover{
    background-color: white;
    transition: background-color 0.3s;
    transition: transform 0.3s;
    transform: translateX(10px);
    padding: 15px;
}
.custom-border {
      border-top: 1px solid #9629E6;
    }
    .custom-border-hover:hover {
      border-top: 1px solid #9629E6;
    }

    .color-price{
      color:#9629E6 ;
      padding-bottom: 15px;
    }
</style>