<script setup>
import { RouterLink,RouterView } from 'vue-router';

</script>

<template>
 
  <!-- RouterLink: Used for navigation between routes without reloading the page. -->
  <RouterLink to="/">Login</RouterLink>
  <RouterLink to="/home">Home</RouterLink> 
  <RouterLink to="/about">About</RouterLink>
  <RouterLink to="/contact">Contact</RouterLink> 

  

  <!-- Vue has a special component called the router-view that will handle the entire process for us. 
   RouterView: A placeholder that renders the matched component for the current route. -->
  <RouterView></RouterView>


</template>

<style scoped>

</style>
