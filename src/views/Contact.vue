<template>
  <div class="contact">
    <div id="contact_content">
      <h1>聯繫資訊</h1>
      <p id="contact_data">
        <ul>
          <li>國立清華大學藝術學院學士班<br></li>
          <li>30014新竹市南大路521號（教學大樓3F）<br></li>
          <li>+886-3-5715131 #78802<br></li>
          <li>ipta@my.nthu.edu.tw</li>
        </ul>
      </p>
    </div>
  </div>
</template>
<style>
#contact_content{
  margin-left:-8px;
  margin-top:-10px;
  width: 185vh;
  height: 100vh;
  border:0px;
  background-size:100% 100%;
  /* background-size:140% 2%; */
  background-image:linear-gradient(to top, rgba(91, 91, 94, 0.445),rgba(24, 24, 36, 0.568)),
    url(https://images.unsplash.com/photo-1531278329486-539bf3bd6d5e?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1525&q=80);
  /*背景圖片，最先寫的在最上層*/
  /* width:1600px; height:1000px; */
}
h1{
  margin: 0px;
  padding: 120px 0 0 0;
}
#contact_data{
  margin: 0px;
  padding: 25px 0 0 10px;
  line-height: 38px;
  text-align:left;
}
ul{
  align-content: center;
  padding: 0 0 0 600px;
}
li{
  font-size:18px;
}
</style>