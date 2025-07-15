<template>
  <section class="banner-section banner-one">

    <div class="banner-carousel">
      <!-- Slide Item -->
      <no-ssr>
      <carousel :items="1" :autoplay="false" :nav="false">

        <div class="slide-item">
          <!-- <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v1_1.jpg);">
          </div> -->
                <div class="image-layer">
                   <!--<video controls autoplay>
    <source src="/assets/images/main-slider/video.mp4" type="video/mp4">
</video> -->

      <video autoplay muted loop>
            <source src="/assets/images/main-slider/video.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>

        </div>

          <div class="auto-container">
            <div class="content-box">
              <div class="content">
                <div class="inner">
                  <div class="sub-title">Creativity Innovation Quality</div>
                  <h2 class="main-heading" style="font-size: 40px;margin-top: 43px;font-weight: 600;">Welcome to<br> Creative Sustainability Group</h2>
                  <!-- <div class="link-box">
                    <nuxt-link to="/about" class="thm-btn">Discover More</nuxt-link>
                  </div> -->
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- Slide Item -->
        <!-- <div class="slide-item">
          <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v1_2.jpg);">
          </div>
          <div class="auto-container">
            <div class="content-box">
              <div class="content">
                <div class="inner">
                  <div class="sub-title">Creativity Innovation Quality</div> -->
                  <!-- <h1>Pioneers<br> in Manufacturing Electrical Products</h1> -->
                  <!-- <div class="link-box">
                    <nuxt-link to="/about" class="thm-btn">Discover More</nuxt-link>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div> -->
        <!-- Slide Item -->
        <!-- <div class="slide-item">
          <div class="image-layer" style="background-image: url(/assets/images/main-slider/slide_v1_3.jpg);">
          </div>
          <div class="auto-container">
            <div class="content-box">
              <div class="content">
                <div class="inner">
                  <div class="sub-title">Creativity Innovation Quality</div> -->
                  <!-- <h1>Welcome to<br> agriculture Form</h1> -->
                  <!-- <div class="link-box">
                    <nuxt-link to="/about" class="thm-btn">Discover More</nuxt-link>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div> -->
      </carousel>
      </no-ssr>
    </div>
  </section>
</template>

<script>

    export default {
      name: "Slider",
      data(){
          return {

          }
      }
    }
</script>

<style scoped>

</style>
