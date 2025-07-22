<template>
  <div>
    <Nav />
    <PageHeader title="Milestones" />
    <Milestones />
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Milestones from "../components/Milestones";
  import Footer from "../components/Footer";
  export default {
    components: {
      Footer,
      Milestones,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Creative Engineering (Pvt) Ltd  | Milestones"
      }
    }
  }
</script>
