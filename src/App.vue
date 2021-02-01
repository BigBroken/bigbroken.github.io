<template>
  <div id="app">
    <div class="background">
      <div class="spacer">
      </div>
      <HelloWorld msg="Ruthie Halberstadt" subMsg="'Scientist'"/>
      <Btn href="https://www.google.com">CV</Btn>
      <Btn href="https://scholar.google.com/citations?user=xt9Rj30AAAAJ&hl">Google Scholar</Btn>
      </div>
      <Bio>
      </Bio>
    </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Btn from './components/Btn.vue'
import Bio from './components/Bio.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Btn,
    Bio
  }
}
</script>

<style>
@media (min-width: 768px){
  .background {
    height:420px;
  }
}
.spacer{
  height:200px;
}

.background{
  height:650px;
    text-align: center;
    color: #fff;
    background-image: url("./assets/tealCover.jpg");
    background-repeat: no-repeat;
    background-attachment: scroll;
    background-position: center center;
    background-size: cover;
}
#app {
  margin-top: -0px !important;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

</style>
