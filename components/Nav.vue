<template>
  <div class="site-header__header-one-wrap">

    <div class="topbar-one">
      <div class="topbar_bg" style="background-image: url(/assets/images/shapes/header-bg.png)"></div>
      <div class="container">
        <div class="topbar-one__left">
          <a href="mailto:info@creative.com.pk"><span class="icon-message"></span>info@creative.com.pk</a>
          <a href="tel:+92-42-35111727"><span class="icon-phone-call"></span>+92-42-35111727</a>
        </div>
        <div class="topbar-one__middle">
          <a href="/" class="main-nav__logo">
            <!-- <p class="font-weight-bold f-20" style="font-size: 24px; color:green">Creative Engineering Pvt</p> -->
            <img src="/assets/images/resources/logo.png" class="main-logo" alt="Creative Sustainability Group" style="width:190px;height:98px;" />
          </a>
        </div>
        <div class="topbar-one__right">
          <div class="topbar-one__social">
            <a href="#"><i class="fab fa-facebook-square"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <!-- <a href="#"><i class="fab fa-instagram"></i></a> -->
            
          </div>
        </div>
      </div>
    </div>

    <header class="main-nav__header-one">
      <nav :class="`header-navigation stricky clearfix ${sticky ? 'stricked-menu stricky-fixed' : ''}`">
        <div class="container clearfix">
          <!-- Brand and toggle get grouped for better mobile display -->
          <div class="main-nav__left">
            <!-- <a href="#" class="main-nav__search search-popup__toggler"><i class="icon-magnifying-glass"></i></a> -->
            <a href="#" class="side-menu__toggler">
              <i @click="mobileToggle = !mobileToggle" class="fa fa-bars"></i>
            </a>
          </div>
          <div class="main-nav__main-navigation">
            <ul class=" main-nav__navigation-box">
              <li class="dropdown current">
                <nuxt-link to="/">Home</nuxt-link>
                <!-- <ul>
                  <li><nuxt-link to="/">Home 01</nuxt-link></li>
                  <li><nuxt-link to="/index2">Home 02</nuxt-link></li>
                  <li><nuxt-link to="/index3">Home 03</nuxt-link></li>
                  <li><nuxt-link to="/index4">Home 04</nuxt-link></li>
                  <li><nuxt-link to="/index5">Home 05</nuxt-link></li>
                  <li class="dropdown"><a href="#">Header Versions</a>
                    <ul>
                      <li><nuxt-link to="/index">Header 01</nuxt-link></li>
                      <li><nuxt-link to="/index2">Header 02</nuxt-link></li>
                      <li><nuxt-link to="/index3">Header 03</nuxt-link></li>
                      <li><nuxt-link to="/index4">Header 04</nuxt-link></li>
                      <li><nuxt-link to="/index5">Header 05</nuxt-link></li>
                    </ul>
                  </li>
                </ul> -->
              </li>
              <li class="dropdown">
                <nuxt-link to="/about-us">About Us</nuxt-link>
                <ul>
                  <li><nuxt-link to="/vision-and-mission">Vision and Mission</nuxt-link></li>
                  <li><nuxt-link to="/milestones">Milestones</nuxt-link></li>
                  <!-- <li><nuxt-link to="/management">Management</nuxt-link></li> -->
                  <!-- <li><nuxt-link to="/service-detail">Associated Companies</nuxt-link></li> -->
                </ul><!-- /.sub-menu -->
              </li>
              <li class="dropdown">
                <nuxt-link to="/products">Products</nuxt-link>
                <ul>
                  <li v-for="product in products"><nuxt-link :to="`/sub-products?name=${product.name}`">{{ product.name }}</nuxt-link></li>
                  <!-- <li><nuxt-link to="/projects_detail">Transmission Line Hardware</nuxt-link></li>
                  <li><nuxt-link to="/projects_detail">Security Boxes & Safety</nuxt-link></li>
                  <li><nuxt-link to="/projects_detail">Fiberglass Composite (FRP-GRP)</nuxt-link></li> -->
                </ul><!-- /.sub-menu -->
              </li>
              <li>
                <nuxt-link to="/certificate">Certifications</nuxt-link>
                <!-- <ul>
                  <li><nuxt-link to="/product">Products</nuxt-link></li>
                  <li><nuxt-link to="/product-detail">Product Detail</nuxt-link></li>
                  <li><nuxt-link to="/cart">Cart</nuxt-link></li>
                  <li><nuxt-link to="/checkout">Checkout</nuxt-link></li>
                </ul>/.sub-menu -->
              </li>
              <li>
                <nuxt-link to="#">Services</nuxt-link>
                <ul>
                  <li><nuxt-link to="#">Sustainability & Environment</nuxt-link></li>
                  <li><nuxt-link to="#">Renewable Energy</nuxt-link></li>
                  </ul>
                </li>
              <li>
                <nuxt-link to="#">Projects</nuxt-link>
                <!-- <ul>
                  <li><nuxt-link to="/about">About</nuxt-link></li>
                  <li><nuxt-link to="/why_choose_us">Why Choose Us</nuxt-link></li>
                  <li><nuxt-link to="/farmers">Farmers</nuxt-link></li>
                  <li><nuxt-link to="/gallery">Gallery</nuxt-link></li>
                </ul> -->
              </li>
              <li class="dropdown">
                <nuxt-link to="#">Jobs</nuxt-link>
                <!-- <ul>
                  <li><nuxt-link to="/news">News</nuxt-link></li>
                  <li><nuxt-link to="/news_detail">News Details</nuxt-link></li>
                </ul>/.sub-menu -->
              </li>
              <li>
                <nuxt-link to="/contact">Contact</nuxt-link>
              </li>
            </ul>
          </div><!-- /.navbar-collapse -->

          <!-- <div class="main-nav__right">
            <div class="icon_cart_box">
              <nuxt-link to="/cart">
                <span class="icon-shopping-cart"></span>
              </nuxt-link>
            </div>
          </div> -->
        </div>
      </nav>


      <nav class="mobile-nav__container" :style="`display: ${mobileToggle ? 'block' : 'none'}`">
        <!-- content is loading via js -->

        <ul class="main-nav__navigation-box">
          <li class="dropdown current">
            <div class="menu-holder">Home<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
        
          </li>
          <li class="dropdown">
            <div class="menu-holder"><nuxt-link to="/about-us">About Us</nuxt-link><button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
            <ul>
              <li><nuxt-link to="/vision-and-mission">Vision & Mission</nuxt-link></li>
              <li><nuxt-link to="/milestones">Milestones</nuxt-link></li>
            </ul><!-- /.sub-menu -->
          </li>
          <!-- <li class="dropdown">
            <div class="menu-holder">Products<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button>
            </div>
            <ul>
              <li><nuxt-link to="/projects">Projects</nuxt-link></li>
              <li><nuxt-link to="/projects_detail">Projects Detail</nuxt-link></li>
            </ul>
          </li> -->
          <li class="dropdown">
            <div class="menu-holder"><nuxt-link to="/products">Products</nuxt-link><button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
                <ul>
                  <li v-for="product in products"><nuxt-link :to="`/sub-products?name=${product.name}`">{{ product.name }}</nuxt-link></li>
                  <!-- <li><nuxt-link to="/projects_detail">Transmission Line Hardware</nuxt-link></li>
                  <li><nuxt-link to="/projects_detail">Security Boxes & Safety</nuxt-link></li>
                  <li><nuxt-link to="/projects_detail">Fiberglass Composite (FRP-GRP)</nuxt-link></li> -->
                </ul>
              </li>

          <li>
            <nuxt-link to="#">Certifications</nuxt-link>
          </li>
          <li class="dropdown">
            <div class="menu-holder">Services<button class="dropdown-btn"><i class="fa fa-angle-right"></i></button></div>
            <ul>
              <li><nuxt-link to="#">Sustainability & Environment</nuxt-link></li>
              <li><nuxt-link to="#">Renewable Energy</nuxt-link></li>
            </ul><!-- /.sub-menu -->
          </li>
          <li>
            <nuxt-link to="#">Projects</nuxt-link>
          </li>
          <li>
            <nuxt-link to="#">Jobs</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/contact">Contact</nuxt-link>
          </li>
        </ul>
      </nav>

    </header>
  </div>
</template>

<script>
 import {products} from '../data.ts'
export default {
  name: "Nav",
  data() {
    return {
      sticky: false,
      mobileToggle: false,
      products: products
    }
  },
  mounted() {
    window.addEventListener('scroll', this.handleScroll);
  },
  methods: {

    handleScroll() {
      if (window.scrollY > 70) {
        this.sticky = true
      } else if (window.scrollY < 70) {
        this.sticky = false
      }
    },
  }
}
</script>

<style scoped></style>
