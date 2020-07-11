<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/hanyul_profile_pic.jpeg">
    <HelloWorld msg_kr="안녕하세요. 이한율입니다."/>
    <HelloWorld msg_en="Hello. My name is hanyul."/>
    <HelloWorld msg_es="Hola. Mi nombre es hanyul"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
