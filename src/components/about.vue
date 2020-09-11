<template>
<div>
 <div id="about">
      <div class="about-title">
        <h1 class="title">About Me</h1>
      </div>
      <div class="about-content">
        <h1>그럼에도 불구하고</h1>
        <section class="about-text">
          안녕하세요 이상연 입니다. 어렸을 때 부터 컴퓨터를 만지는 것을 좋아했습니다. 비록 프로그래밍은 아니었지만 스타크래프트 유즈맵 만들기 등 무언가를 만들고 동작하는게 재미있었습니다.
          진로에 대한 고민을 하면서 내가 잘하면서 좋아할 수 있는 진로를 찾던 도중 프로그래밍애 훙마를 느꼈습니다. 주변 컴퓨터 공학과 출신인 지인들에게 자문도 구하면서 점차 방향을 잡고
          프로그래밍을 접하게 되었습니다. 비록 비전공이지만 취업만을 위해 급하게 하는 것보다 점진적으로 기본적인 CS를 여러 매체를 통해 접하고 공부하였습니다. 현재는 프론트엔드 분야에 관심을 가지고
          Vue js와 Css기초 Html 등을 학습중에 있습니다. 전공자들 보다 전공지식이 모자를 수 있지만 그럼에도 불구하고 이를 채워나가고 점차 발전 할 수 있는 인재가 되고 싶습니다.   
        </section>
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
#about {
    display: flex;
  justify-content: flex-start;
    margin: 0;
    background: #fff;
    height: 100%;
    width: 100%;

}
#about .about-title {
    margin-left: 6vw;
    margin-right: 12vw;
    width: 25vw;
    box-sizing: border-box;
    text-align: center;
    align-self: center;
}
.title {
  position: relative;
    display: inline-block;
    font-size: 2.4em;
    font-weight: 400;
    margin: 30px 0;
}
#about .about-content {
  font-family: 'Noto Sans KR',sans-serif;
    margin-bottom: 4rem;
    margin-top: 4rem;
    box-sizing: border-box;
    padding: 1rem;
    margin-right: 8vw;
    width: 100%;
}
</style>