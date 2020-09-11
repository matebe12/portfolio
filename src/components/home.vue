<template>
  <div id="home">
        <span>이상연의 Develop Portfolio</span>
  </div>
</template>

<script>
export default {

}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@500&display=swap');
#home {
  background: url('../assets/background.png');
  background-attachment: fixed;
  background-size: cover;
  position:relative;
  text-align: center;
  height: 100vh;
  align-items: center;
  display: flex;
  justify-content: center;
}
#home span{
font-family: 'Noto Sans KR', sans-serif;
  color: aliceblue;
    font-size: 4vw;
    white-space: pre;
    line-height: 1;
    letter-spacing: .1rem;
    padding-top: .2em;
    animation-duration: 2s;
    animation-name: slidein;
}


@keyframes slidein {
  from {
    margin-left: 100%;
    width: 300%
  }

  to {
    margin-left: 0%;
    width: 100%;
  }
  75% {
  font-size: 300%;
  margin-left: 25%;
  width: 150%;
  }
}
</style>