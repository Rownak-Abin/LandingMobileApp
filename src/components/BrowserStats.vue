<script setup>

const site = "https://preview.colorlib.com/theme/nexus/#";
const browser = "/assets/browser.png"

</script>

<template>
  <section class="made_life_area p_120">
    <div class="container">
      <div class="made_life_inner">
        <div class="row made_life_text">
          <div class="col-lg-6">
            <div class="left_side_text">
              <h3>We’ve made a life <br />that will change you</h3>
              <h6>We are here to listen from you deliver exellence</h6>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod temp or incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim.
              </p>
              <a
                class="main_btn"
                :href="site"
                >Get Started Now</a
              >
            </div>
          </div>
          <div class="col-lg-6">
            <div class="chart_img">
              <img
                class="img-fluid"
                :src="browser"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style>
</style>