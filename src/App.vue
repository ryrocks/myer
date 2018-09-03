<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Header></Header>
    <Introduction></Introduction>
    <Secondary></Secondary>
    <Third></Third>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Introduction from "./components/Introduction.vue";
import Secondary from "./components/Secondary.vue";
import Third from "./components/Third.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "app",
  components: {
    Header,
    Introduction,
    Secondary,
    Third,
    Footer
  }
};
</script>

<style>
#app {
  font-family: "Open Sans", "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* common style */
.d-flex {
  display: flex;
}

.justify-content-between {
  justify-content: space-between;
}
.justify-content-center {
  justify-content: center;
}

.align-items-center {
  align-items: center;
}

.flex-column {
  flex-direction: column;
}

.flex-1 {
  flex: 1;
}

.flex-2 {
  flex: 2;
}

.flex-3 {
  flex: 3;
}

.text-left {
  text-align: left;
}

.text-center {
  text-align: center;
}

.text-right {
  text-align: right;
}
</style>
