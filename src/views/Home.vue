<template>
  <div class="home">
    <img
      alt="Vue logo"
      src="../assets/logo.png"
    >
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Helloi18n />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import Helloi18n from '@/components/HelloI18n';

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Helloi18n,
  },
};
</script>
