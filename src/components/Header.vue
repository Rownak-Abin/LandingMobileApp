<script setup>

const site = "https://preview.colorlib.com/theme/nexus/"
const navSite = "nav-item"
const logo = "/assets/logo.png"

</script>


<template >

<header class="header_area">
    <div class="main_menu">
      <nav class="navbar navbar-expand-lg navbar-light">
        <div class="container box_1620">

          <a class="navbar-brand logo_h" :href="site + 'index.html'">
            
            <img :src="logo" alt=""></a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>

          <div class="collapse navbar-collapse offset" id="navbarSupportedContent">
            <ul class="nav navbar-nav menu_nav justify-content-center">
              <li class="nav-item active"><a class="nav-link"
                  :href="site + 'index.html'">Home</a></li>
              <li :class="navSite"><a class="nav-link"
                  :href="site + 'about-us.html'">About</a></li>
              <li :class="navSite"><a class="nav-link"
                  :href="site + 'services.html'">Services</a>
              </li>
              <li class="nav-item submenu dropdown">
                <a :href="site + '#'" class="nav-link dropdown-toggle"
                  data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Pages</a>
                <ul class="dropdown-menu">
                  <li :class="navSite"><a class="nav-link"
                      :href="site + 'price.html'">Pricing</a>
                  </li>
                  <li :class="navSite"><a class="nav-link"
                      :href="site + 'elements.html'">Elements</a></li>
                </ul>
              </li>
              <li class="nav-item submenu dropdown">
                <a :href="site + '#'" class="nav-link dropdown-toggle"
                  data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Blog</a>
                <ul class="dropdown-menu">
                  <li :class="navSite"><a class="nav-link"
                      :href="site + 'blog.html'">Blog</a></li>
                  <li :class="navSite"><a class="nav-link"
                      :href="site + 'single-blog.html'">Blog Details</a></li>
                </ul>
              </li>
              <li :class="navSite"><a class="nav-link"
                  :href="site + 'contact.html'">Contact</a></li>
            </ul>
            <ul class="nav navbar-nav navbar-right">
              <li :class="navSite"><a :href="site + '#'" class="tickets_btn">Free Trial</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </header>


</template>

<style>
    
</style>