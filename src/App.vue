<template>
  <div id="app">
    <Navbar />
    <Home /> 
    <About />
    <Skills />
    <Project /> 
  </div>
</template>

<script>
import Navbar from './components/navbar'; 
import Home from './components/home'; 
import About from './components/about'; 
import Skills from './components/skill'; 
import Project from './components/toyproject'; 

export default {
  name: 'App',
  components:{
    Navbar,
    Home,
    About,
    Skills,
    Project,
  }
}
</script>

<style>

body{
  
  margin: 0;
}
</style>
