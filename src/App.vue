<template>
  <div id="app">
    <img src="./assets/logo.png">
    <ShowIp/>
    <VideoPlayer/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import VideoPlayer from './components/VideoPlayer'
import ShowIp from "./components/ShowIp";

export default {
  name: 'App',
  components: {
    ShowIp,
    // HelloWorld
    VideoPlayer
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
