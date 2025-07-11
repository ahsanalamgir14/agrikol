<template>
  <section class="service_detail">
    <div class="container">
      <div class="row">
        <div class="col-xl-4 col-lg-4">
          <div class="service_details_left">
            <ul class="list-unstyled service_all_list">
             
              <li class="active"><nuxt-link to="/about-us">About Us</nuxt-link></li>
              <li><nuxt-link to="/vision-and-mission">Vision and Mission</nuxt-link></li>
              <li><nuxt-link to="/milestones">Milestones</nuxt-link></li>
              <li><nuxt-link to="/management">Management</nuxt-link></li>
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
              <h2>About Us</h2>
              <p class="justify-para">
                The organization was incepted in 1993 with a Vision i.e. to provide our valued customers a vast and comprehensive range of Creative, Innovative and Quality Electrical, Metallurgical and FRP/GRP products, components and customized solutions rightly as per their desires and needs with extended reliability and commitment of after sale services.

                Our Mission is rooted in the guiding philosophy and ethics of total customer satisfaction. Our greatest strength as an ISO 9001:2000 certified organization along with our supremacy as best electrical and engineering group is our unwavering commitment to completely fulfill the customer's needs & wants in a unmatched passion.
                CREATIVE GROUP, Lahore, Pakistan is comprised of four major business units:
                <ul>
                  <li>Creative Engineering (Pvt.) Ltd.</li>
                  <li>Vision Engineering (Pvt.) Ltd.</li>
                  <li>Creative Sustainable Group Ltd.</li>
                </ul>
                The parent company “Creative Engineering” commenced business during 1993 and by the grace of Almighty-God in a period of 23 years it has expanded its business, factories & product lines tremendously & emerged into a Group now known as CREATIVE GROUP. For more information about our company and products, please check the relevant sections.</p>

              <!-- <p class="harvest_innovations_bottom_text">Beyond more stoic this along goodness hey
                this this wow manatee mongoose one as since a far flustered impressive manifest far
                crud opened inside owing punitively around forewent and after wasteful telling
                sprang coldly and spoke less clients. Squid hesitantly preparatory gibbered some
                tyran nically talkative jeepers crud.</p> -->

            </div>
            <!-- <div class="row">
              <div class="col-xl-6 col-lg-6">
                <div class="service_details_single_img_box">
                  <img src="/assets/images/service/service-detail_img_2.jpg" alt="">
                </div>
              </div>
              <div class="col-xl-6 col-lg-6">
                <div class="service_details_single_img_box">
                  <img src="/assets/images/service/service-detail_img_3.jpg" alt="">
                </div>
              </div>
            </div>
            <div class="agriculture_solutions">
              <h3>Agriculture Solutions</h3>
              <p>Lorem ipsum is simply free text used by copytyping refreshing. Neque porro est qui
                dolorem ipsum quia quaed inventore veritatis et quasi architecto beatae vitae dicta
                sunt explicabo. Aelltes port lacus quis enim var sed efficitur turpis gilla sed sit
                amet finibus eros. Lorem Ipsum is simply dummy text of the printing and typesetting
                industry.</p>
            </div>
            <ul class="list-unstyled">
              <li><i class="fa fa-check"></i>Research beyond the business plan</li>
              <li><i class="fa fa-check"></i>Marketing options and rates</li>
              <li><i class="fa fa-check"></i>The ability to turnaround consulting</li>
              <li><i class="fa fa-check"></i>Help companies into more profitable</li>
            </ul>
            <p class="service_details_last_text">Lorem Ipsum has been the ndustry standard dummy text
              ever since the 1500s, when an unknown printer took a galley of type and scrambled it to
              make a type specimen book. It has survived not only five centuries.</p> -->
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
