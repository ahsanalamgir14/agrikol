<template>
  <div>
    <Nav />
    <PageHeader title="About Us" />
    <AboutUs />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import AboutUs from "../components/AboutUs";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      AboutUs,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Creative Engineering (Pvt) Ltd  | About Us"
      }
    }
  }
</script>
