<template>
	<button>
		<a :href="linkDestinazione">{{ msg }}</a>
	</button>
</template>

<script>
export default {
	name: "Button",
	props: {
		msg: String,
		linkDestinazione: String
	}
};
</script>

<style scoped>
button {
	margin: 30px 0;
	background-color: lightskyblue;
	padding: 15px 30px;
	border-radius: 10px;
	box-shadow: 0 4px 8px black;
}
a {
	text-decoration: none;
	color: black;
	font-size: 16px;
	font-weight: 700;
}
</style>
