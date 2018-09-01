<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <section class="brand">
      <img src="https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Flogo.png?1535432056985" />
      <p>
        Lorem Ipsum is simply dummy text<br>of the printing and typesetting industry.
      </p>
    </section>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.brand{
  background:#F7F7F7;
  text-align:center;
  padding:430px 0 0;
}

.brand p{
  font-size:25px;
  margin-bottom:60px;
}
</style>
