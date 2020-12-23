<template>
  <div class="home">
    <div id="block1">
      <HelloWorld />
    </div>
    <div id="block2">
    </div>
  </div>
  
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style>
#block1{
  margin-left:-8px;
  margin-top:-10px;
  width: 185vh;
  height: 100vh;
  border:0px;
  background-size:100% 100%;
  /* background-size:140% 2%; */
  background-image:linear-gradient(to top, rgb(5, 5, 5),rgba(3, 3, 3, 0.18)),
    url(https://images.unsplash.com/photo-1518610424324-79ca316bd290?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80);
  /*背景圖片，最先寫的在最上層*/
  /* width:1600px; height:1000px; */
}
#block2{
  margin-left:-8px;
  margin-top:-10px;
  width: 185vh;
  height: 120vh;
  border:0px;
  background-size:100% 100%;
  background-image:linear-gradient(to top,rgba(3, 3, 3, 0.109),rgba(3, 3, 3, 0.733)),
  url(https://images.unsplash.com/photo-1545255800-61d2b1b8189f?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=2850&q=80);/*背景圖片*/
  /* width:1600px; height:1000px; */
  
}
</style>

