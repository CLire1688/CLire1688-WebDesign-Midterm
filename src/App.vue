<template>
  <div id="app">
    <div id="nav">
      <div style="display:inline; padding:15px"><router-link to="/">HOME </router-link></div>
      <div style="display:inline; padding:15px" ><router-link to="/news">NEWS </router-link></div>
      <div style="display:inline; padding:15px"><router-link to="/about">ABOUT </router-link></div>
      <div style="display:inline; padding:15px"><router-link to="/contact">CONTACT</router-link></div>
    </div>
    <!-- <div id="menu">
      <router-link to="/menu" class="menu" rel="nofollow" style="user-select: auto; right: 25px;">
        <svg viewBox="-1700 0 1999 80" style="user-select: auto;">
          <g class="fill" style="user-select: auto;">
            <path d="M39.5 78.1C18.2 78.1.9 60.8.9 39.5S18.2.9 39.5.9s38.6 17.3 38.6 38.6-17.3 38.6-38.6 38.6zm0-74.9c-20 0-36.3 16.3-36.3 36.3 0 20 16.3 36.3 36.3 36.3 20 0 36.3-16.3 36.3-36.3 0-20-16.3-36.3-36.3-36.3z" style="user-select: auto;"></path>
            <path d="M45.059 18.767v10h-2.9v-3.9l-2.4 3-2.4-3v3.9h-2.9v-10h1.4l3.9 4.9 4-4.9M31.059 42.167v2.3h-8.1v-10h7.8v2.4h-5v1.6h4.2v2.3h-4.2v1.4M57.559 34.467v10h-1.4l-5.1-4.9v4.9h-2.9v-10h1.3l5.2 5v-5M43.859 56.167c0 2.3-1.6 4.2-4.7 4.2s-4.7-1.8-4.7-4.2v-6h2.8v5.2c0 1.8.6 2.4 1.8 2.4 1.2 0 1.9-.6 1.9-2.4v-5.2h2.8v6h.1z" style="user-select: auto;"></path>
          </g>
        </svg>
      </router-link>
    </div> -->
    <router-view/>
    <footer id=footer>
      <div style="display:inline; padding:15px"><router-link to="/">HOME </router-link></div>
      <div style="display:inline; padding:15px" ><router-link to="/news">NEWS </router-link></div>
      <div style="display:inline; padding:15px"><router-link to="/about">ABOUT </router-link></div>
      <div style="display:inline; padding:15px"><router-link to="/contact">CONTACT</router-link></div>
      <!-- A footer for the page. -->
    </footer>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #f9f9fa;
  margin-left:-8px;
  margin-top:-10px;
  width: 184vh;
  height: 72vh;
  border:0px;
  /* background-image:url(https://ipta.nthu.edu.tw/wp-content/uploads/2017/10/BG.jpg);/*背景圖片*/
  /* width:1600px; height:1000px; */
  /* background-size:140% 2%; */ 
}

#router-view {
  background-image:url(https://unsplash.com/photos/d2NY1IKOZ9Q);/*背景圖片2*/
  position:relative;
  top:1000px;left:85px;
}

#nav {
  padding: 25px; 
  background-color: rgb(0, 0, 0);
  color: aliceblue;
}

#nav a {
  font-weight:normal;
  color: #f9faf9;
  text-decoration: none; /*去除預設樣式底線底線*/
}

#nav a.router-link-exact-active {
  color:#597BF2;
  text-decoration: none; /*去除預設樣式底線*/
}


#footer {
  padding: 50px; 
  background-color: rgb(0, 0, 0);
  color: aliceblue;
  border-top-style:solid;
  border-width:0.005px;
  border-color: rgb(116, 115, 115);
  text-decoration: none;
}

#footer a {
  font-weight:normal;
  color: #f9faf9;
  text-decoration: none; /*去除預設樣式底線*/
}

#footer a.router-link-exact-active {
  color:#597BF2;
  text-decoration: none; /*去除預設樣式底線*/
}
</style>
