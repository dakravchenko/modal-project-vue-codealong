<template>
  <SignupFormVue/>
</template>

<script>
import SignupFormVue from './components/SignupForm.vue';
export default {
    name: 'app',
    components: {SignupFormVue}
}
</script>

<style>
#app{
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #444;
  margin-top: 60px;
}
body{
   margin: 0;
   background: #eee 
}
</style>