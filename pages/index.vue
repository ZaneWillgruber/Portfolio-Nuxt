<template>

  <div class="bg-primary cursor">
    <NamePlate />
    <AboutMe />
    <ProjectDetails />
    <Project />
    <Project />
  </div>
</template>

<script>
import NamePlate from '../components/NamePlate.vue';
import 'animate.css';
import AboutMe from '../components/AboutMe.vue';
import Project from '../components/Project.vue';
import ProjectDetails from '../components/ProjectDetails.vue';

export default {
  name: "IndexPage",
  components: { NamePlate, AboutMe, Project, ProjectDetails }
}
</script>

<style>
.text-primary {
    font-family: 'Arvo', sans-serif;
}

.text-secondary {
    font-family: 'Lato', sans-serif;
}

.bg-primary {
  background-color: #F5F5DC;
}

</style>
