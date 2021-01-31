<template>
  <b-jumbotron class="mt-5">
    <b-row>
      <b-col cols="8">
        <h1>Find your Fire Extinguisher</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste iusto illum quidem asperiores, cum nisi aperiam eius ipsa sapiente odit!</p>
        <b-button variant="primary" to="/products">Start Looking</b-button>
      </b-col>
      <b-col cols="4">
        <b-img fluid class="image" src="~assets/svg/fire-extinguisher.svg" alt="fire extinguisher"/>
      </b-col>
    </b-row>
  </b-jumbotron>
</template>

<script>
export default {

}
</script>

<style scoped>
    .image {
       width:12rem;
       height:12rem;
    }
</style>