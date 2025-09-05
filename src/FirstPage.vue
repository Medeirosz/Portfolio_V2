<script setup>
  import Hero from './components/Hero.vue';
  import Projects from './components/Projects.vue';
  import About from './components/About.vue';
</script>

<template>
  <div>
    <Hero/>
    <About/>
    <Projects/>
  </div>

</template>

<style>
  html { scroll-behavior: smooth; }
  body { margin: 0; }
  .full {
    min-height: 100vh;              /* full screen */
    display: flex;
    flex-direction: column;
    align-items: center;            /* horizontal center */
    padding: 4rem 1rem;
  }
</style>
