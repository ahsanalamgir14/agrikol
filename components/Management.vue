<template>
  <section class="service_detail">
    <div class="container">
      <div class="row">
        <div class="col-xl-4 col-lg-4">
          <div class="service_details_left">
            <ul class="list-unstyled service_all_list">
             
              <li><nuxt-link to="/about-us">About Us</nuxt-link></li>
              <li><nuxt-link to="/vision-and-mission">Vision and Mission</nuxt-link></li>
              <li><nuxt-link to="/milestones">Milestones</nuxt-link></li>
              <li class="active"><nuxt-link to="/management">Management</nuxt-link></li>
            </ul>
            <!-- <div class="need_help_box">
              <h2>Need Help?</h2>
              <p>Speak with a human to filling out a form? call corporate office and we will connect
                you with a team member who can help.</p>
              <h3><span class="icon-phone-call"></span>666 888 0000</h3>
            </div> -->
            <!-- <div class="download_file_box">
              <a href="#"><i class="icon-pdf"></i>Download PDF File</a>
            </div> -->
          </div>
        </div>
        <div class="col-xl-8 col-lg-8">
          <div class="service_details_right">
            <div class="service_details_One_img">
              <img src="/assets/images/service/service-detail_img_1.jpg" alt="">
            </div>
            <div class="harvest_innovations">
              <h2>Management</h2>
              <p class="justify-para">
                Coming soon...
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    import FaqOne from "./FaqOne";
    export default {
        name: "ServiceDetail",
      components: {FaqOne}
    }
</script>

<style scoped>

</style>
