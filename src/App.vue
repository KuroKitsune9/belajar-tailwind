<template>
  <div>
    <navbar-component></navbar-component>
    <head-component></head-component>
    <main-component></main-component>
    <footer-component></footer-component>
  </div>
</template>

<script setup>
  import 'flowbite/dist/flowbite.js'

  import NavbarComponent from './NavbarComponent.vue'
  import HeadComponent from './HeadComponent.vue'
  import MainComponent from './MainComponent.vue'
  import FooterComponent from './FooterComponent.vue'
</script>