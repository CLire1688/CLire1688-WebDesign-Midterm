<template>
  <div class="hello">
    <div id="intro">
      <h2>國立清華大學</h2>
      <h1>藝術學院學士班</h1>
      <button id="button1" type="button">Learn more</button>
      <div class="context">
        <p id=introduction>
          清華大學2018年成立藝術學院〝科技藝術〞跨域「學士班」，結合創新科技，<br>
          如各種互動感測技術、虛擬實境、物聯網、人工智慧、大數據分析、基因工程…，<br>
          把「科技」與「藝術」結合視為「未來文化學」，培養前瞻性、跨域研究與創作人才。
        </p>
      </div>
    </div>
    <div id="announce">
      <div id="anno1">
        <h4>《那顆Ｇ1咻！》藝術學院學士班第一屆系展 得獎名單</h4>
        <p align="left">Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, <br>
          sed quia consequuntur magni dolores eos qui ratione voluptatem sequi <br>
          nesciunt. Neque porro quisquam est.</p>
        <button id="button2" type="button">Learn more</button>
      </div>
      <div id="anno2">
        <h4> 2020春之清華 – 藝術卓越獎 科技藝術類 得獎名單</h4>
        <p align="left">Amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore <br>
          et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation <br>
          ullamco laboris nisi.</p>
        <button id="button3" type="button">Learn more</button>
      </div>
      <div id="anno3">
        <h4> 2020藝術學院學士班春之清華獎學金 獲獎名單</h4>
        <p align="left">Consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. <br>
          Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, <br>
          consectetur, adipisci velit, sed quia non numquam.</p>
        <button id="button4" type="button">Learn more</button>
      </div>
      <div id="anno4">
        <h4> 徵聘『助理教授級以上』專任教師1名</h4>
        <p align="left">Eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui <br>
          dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non <br>
          numquam eius modi tempora.</p>
        <button id="button5" type="button">Learn more</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

h1{ /*藝術學院學士班*/
  font-size: 3.6em;
  text-align: center;
  padding: 10px 0px 0px 0px;
  /* text-align: left;
  padding: 5px 0px 0px 165px; */
  margin:0 0 0 0;
}
h2{
  font-size: 2em;
  text-align: center;
  padding: 130px 0px 0px 0px;
  margin:0 0 0 0;
  /* text-align:left;
  padding: 75px 0px 0px 100px; */
}
#introduction{
  text-align: center;
  padding: 30px 0px 0px 0px;
  margin:0 0 0 0;
}
button{
  width:125px;
  height:40px;
  font-size:16px;
  border-radius:5px;
  color: #d4ddfa;
  background-color:#2b46a7d2;
  /* background-color: #42b983; */
  border:2px blue none;
  margin:30px 0 0 0;
}
#button1{
  width:165px;
  height:49px;
  font-size:18px;
  font-weight:bold;
  border-radius:8px;
  color: #d4ddfa;
  background-color:#2b46a7;
  /* background-color: #42b983; */
  border:2px blue none;
  position:relative;
  top:290px;left:0px;
  float:center;
}

#announce{
  text-align:left;
  position:relative;
  left:100px;
}
#anno1{
  position:relative;
  top:582px;left:0px;
}

#anno2{
  position:relative;
  top:378px;left:700px;
}

#anno3{
  position:relative;
  top:510px;left:0px;
}

#anno4{
  position:relative;
  top:306px;left:700px;
}

h5 {
  margin: 40px 0 0;
}

p {
  margin: 2px 0 0;
  font-weight:lighter;
}


</style>
