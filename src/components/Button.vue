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

<style></style>
