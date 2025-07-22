<template>
  <section class="service_detail">
    <div class="container">
      <div class="row">
        <div class="col-xl-4 col-lg-4">
          <div class="service_details_left">
            <ul class="list-unstyled service_all_list">
             
              <li><nuxt-link to="/about-us">About Us</nuxt-link></li>
              <li><nuxt-link to="/vision-and-mission">Vision and Mission</nuxt-link></li>
              <li class="active"><nuxt-link to="/milestones">Milestones</nuxt-link></li>
              <!-- <li><nuxt-link to="/management">Management</nuxt-link></li> -->
            </ul>
            <div class="need_help_box">
              <h2>Need Help?</h2>
              <p>Speak with a human to filling out a form? call corporate office and we will connect
                you with a team member who can help.</p>
              <h3><span class="icon-phone-call"></span>666 888 0000</h3>
            </div>
            <div class="download_file_box">
              <a href="#"><i class="icon-pdf"></i>Download PDF File</a>
            </div>
          </div>
        </div>
        <div class="col-xl-8 col-lg-8">
          <div class="service_details_right">
            <div class="service_details_One_img">
              <img src="/assets/images/service/service-detail_img_1.jpg" alt="">
            </div>
            <div class="harvest_innovations">
              <h2>Milestones</h2>
              <p class="justify-para">
                Creative Sustainability Group is under a process of constant innovation and extention in terms of its product line by introducing vast range of products. Below is the list of milestone achieved so far and still more to come.
                 <ul>
                  <li>1993: Inception of parent company Creative Engineering Pvt. Ltd. for manufacturing of Electrical Line Hardware and a wide variety of related products.</li>
                  <li>2003: New sister company, Vision Engineering Pvt. Ltd. was founded for production of PCC Poles, Spun Poles and Steel Structures etc.</li>
                  <li>2005: ISO 9001:2000 Certified.
                </li>
                  <li>2006: Another sister concern, Creative Electronics Pvt. Ltd. was founded for production of Energy Meters and other accessories.</li>
                  <!-- <li>2008: Creative Plastics and Manufacturing Industries came in to existence with substantial capacity of producing Injection Molding Products.</li> -->
                  <li>2010: Another state of the art unit for GRP/FRP pipe manufacturing and other composite products was established.</li>
                  <li>2012: A novel industrial scale Biogas-Bioenergy facility had been installed and become operational.</li>
                  <li>2015: ISO 9001:2015 (Quality Management Standard) and ISO 14001:2015 (Environmental Management Standard) Certifications achieved.</li>
                  <li>2017: Another large-commercial scale Biogas cum Biofertilizer processing facility was established.</li>
                  <li>2023: A new venture organization, Creative Sustanability Solutions has been established for provision of services regarding safeguarding the environmental, economic, and social sustainability.</li>
                </ul>
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
