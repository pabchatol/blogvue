<template>
   <!-- <Nav/> -->
  <div class="about">
    <h1>This is an about page</h1>
    <mytitle :title="aboutTitle"/>  <!-- //utilizar un componente parametrizado -->
  </div>
</template>
<script setup>
// import Nav from '../components/Nav.vue';
import mytitle from '../components/mytitle.vue';  // importar componente
const aboutTitle = "prueba nueva about title"  // asignar un valor al componente, un txt en este caso
</script>
<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
