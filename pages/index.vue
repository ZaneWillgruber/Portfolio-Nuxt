<template>

  <div>
    <NamePlate />
    <AboutMe />
  </div>
</template>

<script>
import NamePlate from '../components/NamePlate.vue';
import 'animate.css';
import AboutMe from '../components/AboutMe.vue';

export default {
  name: "IndexPage",
  components: { NamePlate, AboutMe }
}
</script>
