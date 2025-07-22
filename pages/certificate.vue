<template>
  <div>
    <Nav />
    <PageHeader title="Certificate" />
    <Certificate />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Certificate from "../components/Certificate";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      PageHeader,
      Certificate,
      Nav
    },
    head(){
      return {
        title: "Creative Engineering (Pvt) Ltd  | Certificate"
      }
    }
  }
</script>
