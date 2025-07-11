<template>
  <div>
    <Nav />
    <PageHeader :title="`${product_name}`"/>
    <SubProductPage />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import SubProductPage from "../components/SubProductPage.vue";
  export default {
    components: {
      SubProductPage,
      Footer,
      PageHeader,
      Nav
    },
    data() {
        return {
          product_name: '',
          product: [],
        };
    },
    mounted() {
      this.product_name = this.$route.query.name;
    },
    head(){
      return {
        title: `Creative Engineering (Pvt) Ltd | ${this.product_name}`
      }
    }
  }
</script>
