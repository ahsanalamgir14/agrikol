<template>
  <section class="about_one">
    <div class="container">
      <div class="row">
        <div class="col-xl-6 col-lg-6">
          <div class="about1_img">
            <div class="about1_shape_1"></div>
            <img src="/assets/images/about/about-image.jpg" width="490px" height="687px" alt="About-Img">
            <div class="about1_icon-box">
              <div class="circle">
                <span class="icon-focus"></span>
              </div>
            </div>
            <!-- <div class="about_img_2">
              <img src="/assets/images/about/about-image-2.jpg" width="370px" height="256px" alt="">
            </div> -->
          </div>
        </div>
        <div class="col-xl-6 col-lg-6">
          <div class="block-title text-left">
            <p>Who we are</p>
            <h3>About Us</h3>
            <div class="leaf">
              <img src="/assets/images/resources/leaf.png" alt="">
            </div>
          </div>
          <div class="about_content">
            <div class="text">
              <p>At <b>Creative Sustainability Group</b>, we lead the way in fostering sustainable practices and environmental stewardship. Our commitment lies at the intersection of innovation, resilience, and positive impact. We're committed to delivering high-quality products and services that make a difference. Our products include: <br>

                <ul class="list-unstyled">
                <li><i class="far fa-circle text-success"></i> Distributed Line Hardware</li>
                <li><i class="far fa-circle text-success"></i> Transmission Line Hardware</li>
                <li><i class="far fa-circle text-success"></i> Security Boxes and Safety</li>
                <li><i class="far fa-circle text-success"></i> Fiberglass Composite (FRP/GRP)</li>
              </ul>

              </p>
            </div>
            <!-- <div class="about1_icon_wrap">
              <div class="about1_icon_single">
                <div class="about1_icon">
                  <span class="icon-harvest"></span>
                </div>
                <p>Growing Fruits and Vegetables</p>
              </div>
              <div class="about1_icon_single">
                <div class="about1_icon">
                  <span class="icon-temperature"></span>
                </div>
                <p>Tips for Ripening your Fruits</p>
              </div>
            </div> -->
            <div class="bottom_text">
              <p>But we're more than just manufacturers. Our passion for sustainability drives us to provide comprehensive environmental services and renewable energy solutions.</p>
            </div>
            <div class="about1__button-block">
              <nuxt-link to="/products" class="thm-btn about_one__btn">View Our Products</nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "AboutOne"
    }
</script>

<style scoped>

</style>
