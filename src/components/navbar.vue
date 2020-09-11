<template>
  <header> 
      <nav> 
          <ul>
              <li><a href="#home">Home</a></li>
              <li><a href="#about">About</a></li>
              <li><a href="#skills">Skills</a></li>
              <li><a href="#project">Project</a></li>
              <li><a href="#contact">Contact</a></li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {

}
</script>

<style scoped>
    header{
        position: fixed; 
        z-index: 1;
        width: 95vw;   
    }
    nav {
        position: relative;
        display: block;
        background: black;
        border-radius: 8px 8px 8px 8px;
        opacity: 0.7;
        float: right;
    }
    ul {
        display: flex;
        list-style: none;
         padding: 0;
    }
    ul li {
        padding: 8px 40px;
    }
    ul li a {
        color: aliceblue;
        text-decoration: none;
    }
</style>