<template>
  <div>
    <Nav />
    <PageHeader title="Our Products" />
    <ProductPage />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import ProductPage from "../components/ProductPage";
  export default {
    components: {
      ProductPage,
      Footer,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Creative Engineering (Pvt) Ltd  | Our Projects"
      }
    }
  }
</script>
