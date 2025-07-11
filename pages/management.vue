<template>
  <div>
    <Nav />
    <PageHeader title="Management" />
    <Management />  
    <Footer />
  </div>
</template>

<script>

  import Nav from "../components/Nav";
  import PageHeader from "../components/PageHeader";
  import Footer from "../components/Footer";
  import Management from "../components/Management.vue";
  export default {
    components: {
      Footer,
      Management,
      PageHeader,
      Nav
    },
    head(){
      return {
        title: "Creative Engineering (Pvt) Ltd  | Management"
      }
    }
  }
</script>
