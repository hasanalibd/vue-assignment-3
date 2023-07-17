<script setup>
import hero from "./assets/images/mobile-app.png"
import service from "/src/assets/images/image-14.png"
import apphand from "/src/assets/images/app-hand-top.png"
import playicon from './assets/images/google-play.png'
import appleicon from './assets/images/app-store.png'
</script>

<template>
  <!-- navbar -->
    <div class="container-fluid bg-body-tertiary sticky-top shadow-sm">
      <nav class="navbar navbar-expand-lg ">
        <div class="container">
          <a class="navbar-brand fs-2 fw-semibold" href="#">Launch</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarText">
            <ul class="navbar-nav me-auto mb-2  px-5 mb-lg-0 fs-6 ">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#service">Features</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#pricing">Pricing</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#team">Team</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#contact">Contact</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#about">About</a>
              </li>
            </ul>
            <span class="navbar-text">
              <button type="button" class="btn btn-outline-secondary rounded-4 fs-6 me-3 px-4">Light</button>
              <a class="btn btn-primary rounded-4 fs-6 text-white px-4" href="#" role="button">Register</a>
            </span>
          </div>
        </div>
      </nav>
    </div>

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

  
    <!-- service section -->
    <div class="container-fluid bg-body-tertiary">
      <div class="container py-5" id="service">
      <div class="row d-flex align-items-center justify-content-between flex-column-reverse flex-lg-row">
        <div class="col-12 col-sm-6">
          <img :src="service" class="img-fluid shadow-md  my-3" alt="">
        </div>
        <div class="col-12 col-sm-6 pe-5">
          <h4 class="display-8 fw-semibold text-primary">DIGITAL SERVICES</h4>
          <h2 class="display-4 fw-normal">Selling Digital Services</h2>
          <p class="justify">
            Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast. Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast
          </p>
          <i class="justify">
            “Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia. ”
          </i>
      </div>
      </div>
    </div>
    </div>
    
   
    <!-- backgournd banner -->
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
    
    <!-- pricing section -->
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
              <div><img src="./assets/images/basic.svg" alt="" width="50" class="py-3"></div>
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
              <div><img src="./assets/images/standard.svg" alt="" width="50" class="py-3"></div>
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
              <div><img src="./assets/images/unlimited.svg" alt="" width="50" class="py-3"></div>
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

    <!-- team section -->
    <div class="container py-5" id="team">
      <div class="text-center">
          <h1>Our Team Members</h1>
          <p> 
            Following reasons show advantages of adding AppCo to your lead pages, <br> demos and checkouts evisculate interoperable imperatives rather.
          </p>
      </div>
      <div class="row my-3 ">
        <div class="col-12 col-lg-3 my-element"><img class="img-fluid rounded-circle" src="./assets/images/team-1.jpg" alt=""></div>
        <div class="col-12 col-lg-3 my-element"><img class="img-fluid rounded-circle" src="./assets/images/team-2.jpg" alt=""></div>
        <div class="col-12 col-lg-3 my-element"><img class="img-fluid rounded-circle" src="./assets/images/team-3.jpg" alt=""></div>
        <div class="col-12 col-lg-3 my-element"><img class="img-fluid rounded-circle" src="./assets/images/team-4.jpg" alt=""></div>
      </div>
    </div>

    <!-- contact section -->
    <div class="container-fluid bg-body-tertiary" id="contact">
      <div class="container py-5 ">
      <div class="row">
        <div class="col-12 col-lg-5">
          <h1>Contact with Us</h1>
          <p class="">It's very easy to get in touch with us. Just use the contact form or pay us a visit for a coffee at the office. Dynamically innovate competitive technology after an expanded array of leadership.</p>
          <p class="">It's very easy to get in touch with us. Just use the contact form or pay us a visit for a coffee at the office. Dynamically innovate competitive technology after an expanded array of leadership.</p>
          <p>Head Office <br> 121 King St, Melbourne VIC 3000, Australia</p>
          <p>
            Phone: +61 2 8376 6284 <br>
            Email : hello@yourdomain.com
          </p>
        </div>

        <div class="col-12 col-lg-7">
            <div class="row">
              <h5 class="py-3">Reach us quickly</h5>
              <div class="form-group col-md-6 py-2">
                <input type="text" class="form-control" id="inputEmail4" placeholder="Enter name">
              </div>
              <div class="form-group col-md-6 py-2">
                <input type="email" class="form-control" id="inputPassword4" placeholder="Enter email">
              </div>
              <div class="form-group col-md-6 py-2">
                <input type="number" class="form-control" id="inputEmail4" placeholder="Enter Phone">
              </div>
              <div class="form-group col-md-6 py-2">
                <input type="text" class="form-control" id="inputPassword4" placeholder="Your Compaly">
              </div>
              <div class="form-group">
                <textarea class="form-control" rows="4" cols="50" placeholder="Leave a comment here" id="floatingTextarea"></textarea>
              </div>
            </div>
            <button type="button" class="btn btn-outline-secondary my-2 rounded-pill">Send Message</button>
        </div>
      </div>
    </div>
    </div>

    <!-- about us -->
    <div class="container py-5" id="about">
      <div class="row">
        <div class="col-12 col-lg-8">
          <img class="img-fluid" src="./assets/images/about.svg" alt="">
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

    <!-- footer -->
    <footer class="pt-50 bg-body-tertiary">
    <div class="container pt-5">
      <div class="row">
        <div class="col-md-4 ">
          <div class="footer-link footer-image">
            <img class="mb-3" src="../node_modules/bootstrap-icons/icons/phone-flip.svg" alt="" width="80px">
            <p class="pe-5">Holisticly empower premium architectures without value-added ideas, Seamlessly evole cross-platform experiences.</p>
          </div>
        </div>
        <div class="col-md-2 col-6 sm-center">
          <div class="footer-link">
            <h5>Resources</h5>
            <a href="#"><p>Help</p></a>
            <a href="#"><p>Events</p></a>
            <a href="#"><p>Live Support</p></a>
            <a href="#"><p>Open Sourses</p></a>
            <a href="#"><p>Documentation</p></a>
          </div>
        </div>
        <div class="col-md-2 col-6 sm-center">
          <div class="footer-link">
            <h5>Company</h5>
            <a href="#"><p>About</p></a>
            <a href="#"><p>Careers</p></a>
            <a href="#"><p>Customers</p></a>
            <a href="#"><p>Community</p></a>
            <a href="#"><p>Our Team</p></a>
          </div>
        </div>
        <div class="col-md-4 footer-image">
          <div class="footer-link">
            <h5>Location</h5>
            <p>43 Raymouth Rd. Baltemoer, London 3910</p>
            <p>+1(123)-456-7890</p>
            <p>+1(123)-456-7890</p>
            <a href="#"><p>nfo@mydomain.com</p></a>
          </div>
        </div>
        <hr>
        <div class="container text-center pt-2">
          <p>&copy; 2023 Your Company. All rights reserved.</p>
        </div>
      </div>
    </div>
  </footer>

</template>
<style scoped>
.justify{
  text-align: justify;
}
.hover-backgrund:hover{
  background-color: white;
  transition: background-color 0.3s;
  transition: transform 0.3s;
  transform: translateX(10px);
  padding: 15px;
}

.bg-image {
      background-image: url("assets/images/app-hero-bg.jpg");
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center center;
      background-blend-mode: overlay;
      background-color: rgba(0, 0, 0, 0.8)
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

    .footer-link a{
      text-decoration: none;
    }
</style>
