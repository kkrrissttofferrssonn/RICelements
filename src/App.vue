<template>
  <div id="app">
    <img alt="Vue logo" src="https://vuejs.org/images/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
  <h1>Create a Flex Container</h1>

  <div class="flex-container">
    <div>1</div>
    <div>2</div>
    <div>3</div>
    <div>3</div>
    <div>3</div>
    <div>3</div>
    <div>3</div>
  </div>

  <p>
    A Flexible Layout must have a parent element with the
    <em>display</em> property set to <em>flex</em>.
  </p>

  <p>
    Direct child elements(s) of the flexible container automatically becomes
    flexible items.
  </p>
  <div class="flex-container">
    <div style="flex-grow: 1">1</div>
    <div style="flex-grow: 1">2</div>
    <div style="flex-grow: 8">3</div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
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

.flex-container {
  display: flex;
  background-color: DodgerBlue;
}

.flex-container > div {
  background-color: #f1f1f1;
  margin: 10px;
  padding: 20px;
  font-size: 30px;
}
</style>
