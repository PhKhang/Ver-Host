<template>
  <SimplePage/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import SimplePage from './components/SimplePage.vue'

export default {
  name: 'App',
  components: {
    SimplePage
}
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:ital,wght@0,100;0,200;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,500;1,600;1,700&display=swap');
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:ital,wght@0,100;0,200;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,500;1,600;1,700&family=Noto+Sans+SC:wght@100;300;400;500;700;900&display=swap');

#app {
  font-family: 'IBM Plex Mono', 'Noto Sans SC', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  font-weight: 500;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
