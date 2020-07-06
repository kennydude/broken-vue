<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <FormControl label="test" type="slot">
       <div class="alert alert-info">ISn't that dandy?</div>
    </FormControl>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import FormControl from '@invisibledragon/kit/src/components/FormControl';

export default {
  name: 'App',
  components: {
    HelloWorld,
    FormControl
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
