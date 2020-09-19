<template>
  <div id="project">
      <div class="project-title">
          <h1>Toy Project</h1>
      </div>
      <div class="row">
          <div class="box">
             <a href="https://matebe12.github.io/gersang-trade-search/">
                 <img class="box-image" :src="require('../assets/gersang.png')">
             </a>
             <div class="box-info">
                 <h1>온라인 게임 거상 육의전, 사통팔달 검색 사이트 |  2020.09.11 ~ 2019.09.20</h1>
                 <span>거상에서 지원하는 api를 활용한 육의전, 사통팔달 검색 사이트</span>
                 <p>#Vue #Vuex</p>
                 <a href="https://github.com/matebe12/gersang-trade-search"> <img :src="require('../assets/git.png')" class="git-image"> </a>
             </div>
          </div>
          <div class="box">
             <a href="http://mateshop.duckdns.org">
                 <img class="box-image" :src="require('../assets/shop.png')" alt="쇼핑몰 페이지 방문하기">
             </a>
             <div class="box-info">
                 <h1>Shopping mall | 2020.06.15 ~ 2020.07.15(유지보수는 ing)</h1>
                 <span>Vue, Vuex, Node js, Mysql을 활용한 쇼핑몰 사이트</span>
                 <p>#Vue #Vuex #Node js #Mysql</p>
                 <a href="https://github.com/matebe12/Vue_ShoppingMall"> <img :src="require('../assets/git.png')" class="git-image"> </a>
                 
             </div>
          </div>
          <div class="box">
             <a href="https://matebe12.github.io/Dragonball-Game/">
                 <img class="box-image" :src="require('../assets/game.gif')">
             </a>
             <div class="box-info">
                 <h1>Dragon ball game |  2019.04.01 ~ 2019.04.03</h1>
                 <span>Html, Css, Javascript, jquery를 활용한 웹 게임</span>
                 <p>#Vue #Vuex #Node js #Mysql</p>
                 <a href="https://github.com/matebe12/Dragonball-Game"> <img :src="require('../assets/git.png')" class="git-image"> </a>
             </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Nanum+Pen+Script&display=swap');
#project {
    background: #151c1f;
    border-top: 2px solid #151c1f;
    height: 100%;
    width: 100%;
    margin-bottom: 0;
}
.project-title {
    text-align: center;
    color: #fff;
    margin-bottom: 3em;
}
.project-title h1{
    font-family: 'Noto Sans KR',sans-serif;
    font-size: 2.4em;
    font-weight: 400;
}
.row {
    display: flex;
    flex-wrap: wrap;
}
.box {
    height: 360px;
    width: 100%;
    max-width: 80vw;
    border-radius: 8px 12px 4px 4px;
    margin: 0 auto 30px;
    background: #fff;
    box-shadow: 0 3px 6px rgba(0,0,0,.2), 0 3px 6px rgba(0,0,0,.2);
}
.box-image {
    float: left;
    width: 35%;
    height: 360px;
    margin-right: 2rem;
}
.box-info {
    font-family: 'Nanum Pen Script', cursive;
    padding: 14px;
}
.box-info span{
    font-family: 'Nanum Pen Script', cursive;
    font-size: 2rem;
}
.box-info p {
    margin-top: 5%;
    font-size: 2rem;
    cursor: pointer;
}
.git-image {
 width:30px;
 height: 30px;
}
</style>