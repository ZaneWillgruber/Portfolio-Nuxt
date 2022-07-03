<template>

  <div>
    <NamePlate />
    <AboutMe />
    <Project />
  </div>
</template>

<script>
import NamePlate from '../components/NamePlate.vue';
import 'animate.css';
import AboutMe from '../components/AboutMe.vue';
import Project from '../components/Project.vue';

export default {
  name: "IndexPage",
  components: { NamePlate, AboutMe, Project }
}
</script>

<style>
.text-primary {
    font-family: 'Arvo', sans-serif;
}

.text-secondary {
    font-family: 'Lato', sans-serif;
}
</style>
