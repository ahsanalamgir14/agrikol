<template>

  <section class="page-header" style="background-color: #0009">
    <div class="container">
      <h2>{{ title }}</h2>
      <ul class="thm-breadcrumb list-unstyled">
        <li><nuxt-link to="/">Home</nuxt-link></li>
        <li><span>{{ title }}</span></li>
      </ul>
    </div>
  </section>

</template>

<script>
  export default {
    name: "PageHeader",
    props: {
      title: {
        type: String
      }
    }

  }
</script>

<style scoped>

</style>
