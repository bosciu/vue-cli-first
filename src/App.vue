<template>
	<div id="app">
		<img alt="Vue logo" src="./assets/logo.png" />
		<Title />
		<Hero />
	</div>
</template>

<script>
import Hero from "./components/Hero.vue";
import Title from "./components/Title";

export default {
	name: "App",
	components: {
		Title,
		Hero
	}
};
</script>

<style lang="scss">
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	position: relative;
	margin-top: 60px;
}
* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}
</style>
