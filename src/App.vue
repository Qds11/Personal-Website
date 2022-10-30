<template>
  <div>
    <TopBar class="mt-4" />

    <AboutMe id="about" class="mb-5" />


    <Projects id="proj" class="mt-5 " />

    <Resume id="resume" class="mt-5 " />

    <Footer class="mt-5 mb-3"/>
  </div>
</template>

<script>
  import TopBar from './components/TopBar.vue'
  import AboutMe from './components/AboutMe.vue'
  import Resume from './components/Resume.vue'
  import Footer from './components/Footer.vue'
  import Projects from './components/Projects.vue'


  export default {
    name: 'App',
    components: {
      TopBar,
      AboutMe,
      Footer,
      Resume,
      Projects
    },


  }
</script>

<style>
  body,
  html,
  #app {
    font-family: 'Consolas';
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;

    min-height: 100%;
    height: auto;
    /* width: 100%;*/
    overflow-x: hidden;
    background-color: black;
    color: rgb(173, 175, 174);

  }
  h1, h2{
  color: #384f66;
  }

  hr {
      display: block;
    background-color: white;
    width: 70%;
   margin:auto;


  }
</style>