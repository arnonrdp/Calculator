<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
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
@font-face {
	font-family: "RobotoMono";
	src: url("./fonts/RobotoMono-Thin.ttf");
}
* {
	font-family: "RobotoMono", monospace;
}
body {
	margin: 0;
}
#app {
	display: flex;
	flex-direction: column;
	height: 100vh;
	justify-content: center;
	align-items: center;
	text-align: center;
	color: #fff;
	background: linear-gradient(to right, rgb(83, 105, 118), rgb(41, 46, 73));
}
</style>
