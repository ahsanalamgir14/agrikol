<template>
  <div class="brand-one">
    <div class="container">
      <div class="row">
        <div class="col-xl-12">
          <div class="block-title text-center">
            <h3>Our Clients</h3>
            <div class="leaf">
            <img src="/assets/images/resources/leaf.png" alt="">
            </div>
          </div>
          <div class="brand-one-carousel">
            <no-ssr>
              <carousel :autoplay="true" :dots="false" :nav="false" :responsive="{0: {items: 1},640: {items: 2},992: {items: 3},1024: {items: 5}}">
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/wapda-logo.png" alt="WAPDA LOGO" title="WAPDA"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/lesco-logo.png" alt="LESCO" title="LESCO"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/fesco-logo.png" alt="FESCO" title="FESCO"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/gepco-logo.png" alt="GEPCO" title="GEPCO"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/railways-logo.png" alt="brand" title="Pak"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/wapda-logo.png" alt="brand" title="WAPDA"></a>
            </div>
            <!-- <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-1-2.png" alt="brand" title="Smiley face"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-1-3.png" alt="brand" title="Smiley face"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-1-4.png" alt="brand" title="Smiley face"></a>
            </div>
            <div class="single_brand_item">
              <a href="#"><img src="/assets/images/resources/brand-1-5.png" alt="brand" title="Smiley face"></a>
            </div> -->
              </carousel>
            </no-ssr>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        name: "BrandOne"
    }
</script>

<style scoped>

</style>
