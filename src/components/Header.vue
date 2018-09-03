<template>
  <header class="d-flex justify-content-between">
    <div class="home">
        <a href=""></a>
    </div>
     <div class="d-flex wrapper align-items-center ">
        <span class="text-right">Brought to you by</span>
        <div class="logo">
        </div>
        
     </div>
  </header>
</template>

<script>
// export default {
//   name: "Header",
//   props: {
//     msg: String
//   }
// };
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
header {
  height: 60px;
  width: 100%;
  position: fixed;
  background-color: #fff;
}

.home {
    width: 100px;
    margin-left: 120px;
}
.home a {
    display: block;
    height: 100%;
    background: url(https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Flogo_whimn%20small.svg?1535432057034) center no-repeat;
    background-size: contain;
}

header .wrapper {
    margin-right: 120px;
}

header .wrapper span {
    width: 65px;
    font-size: 10px;
    margin: 0 25px;
}

.logo {
    width: 135px;
    height: 100%;
    background: url(https://cdn.glitch.com/4fe2938a-963f-4754-a48c-0af2e2df417d%2Flogo.png?1535432056985) center no-repeat;
    background-size: contain;
}
</style>
