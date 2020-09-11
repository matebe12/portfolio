<template>
  <footer>
      <div class="footer">
          <ul>
            <li class="li-f"><a href="https://github.com/matebe12/Dragonball-Game"> <img :src="require('../assets/git.png')" class="git-image"> </a></li>
            <li><span>이 사이트는 개발 포트폴리오 사이트 입니다.</span></li>
          </ul>
          
      </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style>
footer {
    width: 100%;
}
.footer {
    display: flex;
    background: gray;
    padding: 1%;
    justify-content: center;
    justify-items: unset;
}
.git-image {
    width:30px;
    height: 30px;
}
ul {
    list-style: none;
}
ul .li-f {
    text-align: center;
}
</style>