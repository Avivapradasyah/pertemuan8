<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'


</script>



<template>
  <TugasPW/>
  

</template>

<script>
import TugasPW from './components/TugasPW.vue';

export default {
  name: 'App',
  components: {
    TugasPW,
  },
};
</script>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

</style>
