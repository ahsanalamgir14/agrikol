<template>
  <section class="recent-product our_projects">
    <div class="container">
      <div class="row">
        <div class="col-xl-4 col-lg-4" v-for="item in product.sub_products">
          <div class="recent_project_single mrb-30">
            <div class="project_img_box">
              <!-- dynamic image -->
              <img src="/assets/images/product/recent-pro-img-1.jpg" alt="Recent Project Img">
              <div class="project_content">
                <h3>{{ item.name }}</h3>
              </div>
              <div class="hover_box">
                <nuxt-link to="/projects_detail"><span class="icon-left-arrow"></span></nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- <div class="row">
        <div class="col-xl-12">
          <div class="our_projects_btn">
            <a href="#" class="thm-btn">Load More Projects</a>
          </div>
        </div>
      </div> -->
    </div>
  </section>
</template>

<script>
    import {products} from '../data.ts'
    export default {
        name: "ProjectPage",
        data() {
            return {
              product_name: '',
              product: [],
            };
        },
        mounted() {
          this.product_name = this.$route.query.name;
          this.product = products.find(product => product.name.toLowerCase().includes(name.toLowerCase()));
        },
        methods: {
        }
    }
</script>

<style scoped>
  .container {
    padding: 20px;
  }
</style>
