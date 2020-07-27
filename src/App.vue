<template>
  <div id="app">
    <TochukwuUzochukwu MyName="Tochukwu Uzochukwu"/>
  </div>
</template>

<script>
import TochukwuUzochukwu from './components/TochukwuUzochukwu.vue'

export default {
  name: 'App',
  components: {
    TochukwuUzochukwu
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
