<template>
  <div>
    <Nav />
    <PageHeader title="Vision and Mission " />
    <VisionAndMission />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import VisionAndMission from "../components/VisionAndMission";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      VisionAndMission,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Creative Engineering (Pvt) Ltd  | Vision and Mission"
      }
    }
  }
</script>
