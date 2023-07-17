<script setup>

const site = "https://preview.colorlib.com/theme/nexus/#";
const img = "/assets/home-left-1.png"

</script>

<template>

    <section class="home_banner_area">
    <div class="banner_inner">
      <div class="container">
        <div class="row">
          <div class="col-lg-5">
            <div class="banner_content">
              <h2>Mass People <br>Oriented Software</h2>
              <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et
                dolore magna aliqua. Ut enim ad minim. sed do eiusmod tempor incididunt.</p>
              <a class="banner_btn" :href="site">Get Started</a>
              <a class="banner_btn2" :href="site">Download</a>
            </div>
          </div>
          <div class="col-lg-7">
            <div class="home_left_img">
              <img class="img-fluid" :src="img" alt="">
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
   
</template>

<style>
    
</style>