<template>
  <section class="recent-project">
    <div class="container">
      <div class="block-title text-center">
        <p>explore projects</p>
        <h3>our Recent projects</h3>
        <div class="leaf">
          <img src="/assets/images/resources/leaf.png" alt="">
        </div>
      </div>
      <div class="row">
        <div class="col-xl-4 col-lg-4">
          <div class="recent_project_single wow fadeInUp" data-wow-delay="300ms">
            <div class="project_img_box">
              <img src="/assets/images/product/solar-power.jpg" class="project-img" alt="Recent Project Img">
              <div class="project_content">
                <h3>Solar<br>Power</h3>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4">
          <div class="recent_project_single wow fadeInUp" data-wow-delay="600ms">
            <div class="project_img_box">
              <img src="/assets/images/product/wastewater.jpg" class="project-img" alt="Recent Project Img">
              <div class="project_content">
                <h3>Waste<br>Water</h3>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-lg-4 wow fadeInUp" data-wow-delay="900ms">
          <div class="recent_project_single">
            <div class="project_img_box">
              <img src="/assets/images/product/solar-lights.jpg" class="project-img" alt="Recent Project Img">
              <div class="project_content">
                <h3>Solar<br>Lights</h3>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "RecentProject"
}
</script>

<style scoped>
.project-img {
  width: 100%;
  height: 480px;
  object-fit: cover;
  display: block;
}
</style>
