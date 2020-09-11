<template>
  <div id="skills">
      <div class="skill-title">
          <h1>Skills</h1>
      </div>
      <div class="skill-content">
          <h2 class="skill-title">Language</h2>
          <span class="skill-content">
              <div class="skill-box">
                  <div class="skill-image java">
                      <div class="skill-label">중급</div>
                  </div>
                  <div class="skill-image javascript">
                      <div class="skill-label">중급</div>
                  </div>
              </div>
          </span>
          <h2 class="skill-title">Web Language, Library</h2>
          <span class="skill-content">
              <div class="skill-box">
                  <div class="skill-image html">
                      <div class="skill-label">중급</div>
                  </div>
                  <div class="skill-image css">
                      <div class="skill-label">초급</div>
                  </div>
                  <div class="skill-image jquery">
                      <div class="skill-label">초급</div>
                  </div>
                  <div class="skill-image ajax">
                      <div class="skill-label">초급</div>
                  </div>
                  <div class="skill-image axios">
                      <div class="skill-label">초급</div>
                  </div>
                  <div class="skill-image typescript">
                      <div class="skill-label">초급</div>
                  </div>
              </div>
          </span>
          <h2 class="skill-title">FrameWork</h2>
          <span class="skill-content">
              <div class="skill-box">
                  <div class="skill-image node">
                      <div class="skill-label">초급</div>
                  </div>
                  <div class="skill-image spring">
                      <div class="skill-label">초급</div>
                  </div>
                  <div class="skill-image vue">
                      <div class="skill-label">중급</div>
                  </div>
                  <div class="skill-image react">
                      <div class="skill-label">초급</div>
                  </div>
              </div>
          </span>
          <h2 class="skill-title">DataBase</h2>
          <span class="skill-content">
              <div class="skill-box">
                  <div class="skill-image mysql">
                      <div class="skill-label">초급</div>
                  </div>
              </div>
          </span>
          <h2 class="skill-title">Etc</h2>
          <span class="skill-content">
              <div class="skill-box">
                  <div class="skill-image git">
                      <div class="skill-label">초급</div>
                  </div>
                  <div class="skill-image svn">
                      <div class="skill-label">초급</div>
                  </div>
              </div>
          </span>
      </div>
      
  </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@500&display=swap');
    #skills {
        background: #eee;
        height: 100%;
        width: 100%;
        margin: 0 auto;
        text-align: center;
        padding-bottom: 5rem;
    }
    #skill-title h1 {
        font-family: 'Noto Sans KR',sans-serif;
        font-size: 2.4em;
        font-weight: 400;
    }
    .skill-title {
        position: relative;
        display: block;
        margin: 30px 0;
        text-decoration: underline;
    }
    .skill-image {
        text-align: center;
        display: inline-block;
        width: 150px;
        height: 150px;
        border-radius: 30px 30px;
        background-size: cover;
        background-repeat: no-repeat;
        margin-right: 2rem;
        box-shadow: 0 3px 6px rgba(0,0,0,.2), 0 3px 6px rgba(0,0,0,.2);
    }
    .java {
        background-image: url('../assets/java.png');
    }
    .javascript {
        background-image: url('../assets/javascript.png');
    }
    .html {
        background-image: url('../assets/html.png');
    }
    .css {
        background-image: url('../assets/css.png');
    }
    .jquery {
        background-image: url('../assets/jquery.png');
    }
    .ajax {
        background-image: url('../assets/ajax.png');
    }
    .axios {
        background-image: url('../assets/axios.png');
    }
    .typescript {
        background-image: url('../assets/typescript.png');
    } 
    .node {
        background-image: url('../assets/node.png');
    }
    .spring {
        background-image: url('../assets/spring.png');
    }
    .vue {
        background-image: url('../assets/vue.png');
    }
    .react {
        background-image: url('../assets/react.png');
    }
    .mysql {
        background-image: url('../assets/mysql.png');
    }
    .git {
        background-image: url('../assets/git.png');
    }
    .svn {
        background-image: url('../assets/svn.png');
    }
    
    .skill-box {
        display: flex;
        text-align: center;
        justify-content: center;
    }
    .skill-label {
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #000;
        border-radius: 30px 30px;
        width: 130px;
        height: 130px;
        padding: 10px;
        opacity: 0.2;
        font-weight: 400;
        font-size: 1rem;
        color: #fff;
        visibility: hidden;
        transition-duration: 0.2s;
    }
    .skill-image:hover .skill-label{
        opacity: 1.0;
        visibility: visible;
        transition-duration: 0.2s;
    }
</style>