<script setup>

  const site = "https://preview.colorlib.com/theme/nexus/#"
  const copyright = ""

</script>
<template>
   <footer class="footer_area p_120">
  <div class="container">
    <div class="row footer_inner">
      <div class="col-lg-5 col-sm-6">
        <aside class="f_widget ab_widget">
          <div class="f_title">
            <h3>About Me</h3>
          </div>
          <p>Do you want to be even more successful? Learn to love learning and growth. The more effort you put into
            improving your skills,</p>
          <p>
            Copyright ©2023 All rights reserved | This template is made with <i class="fa fa-heart-o"
              aria-hidden="true"></i> by <a href="https://colorlib.com/" target="_blank">Colorlib</a>
          </p>
        </aside>
      </div>
      <div class="col-lg-5 col-sm-6">
        <aside class="f_widget news_widget">
          <div class="f_title">
            <h3>Newsletter</h3>
          </div>
          <p>Stay updated with our latest trends</p>
          <div id="mc_embed_signup">
            <form target="_blank"
              action="https://spondonit.us12.list-manage.com/subscribe/post?u=1462626880ade1ac87bd9c93a&amp;id=92a4423d01"
              method="get" class="subscribe_form relative" novalidate="true">
              <div class="input-group d-flex flex-row">
                <input name="EMAIL" placeholder="Enter email address" onfocus="this.placeholder = &#39;&#39;"
                  onblur="this.placeholder = &#39;Email Address &#39;" required="" type="email">
                <button class="btn sub-btn"><span class="lnr lnr-arrow-right"></span></button>
              </div>
              <div class="mt-10 info"></div>
            </form>
          </div>
        </aside>
      </div>
      <div class="col-lg-2">
        <aside class="f_widget social_widget">
          <div class="f_title">
            <h3>Follow Me</h3>
          </div>
          <p>Let us be social</p>
          <ul class="list">
            <li><a :href="site"><i class="fa fa-facebook"></i></a></li>
            <li><a :href="site"><i class="fa fa-twitter"></i></a></li>
            <li><a :href="site"><i class="fa fa-dribbble"></i></a></li>
            <li><a :href="site"><i class="fa fa-behance"></i></a></li>
          </ul>
        </aside>
      </div>
    </div>
  </div>
</footer>
</template>

<style>
    
</style>