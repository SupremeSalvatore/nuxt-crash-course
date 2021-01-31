<template>
  <b-navbar toggleable="lg" type="dark" variant="dark">
    <NuxtLink class="navbar-brand" to="/">Fireby</NuxtLink>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
    <b-collapse id="nav-collapse" is-nav>
        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <NuxtLink to="/products" class="nav-link">Products</NuxtLink>
          <NuxtLink to="/my-items" class="nav-link">My Items</NuxtLink>
        </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>

</style>