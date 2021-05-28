<template>
	<div id="container">
		<div id="text-container">
			<h2>Signori e signore, ecco a voi i famosi "Componenti"!</h2>
			<p>
				I componenti sono utili per spezzettare la complessità di
				un'applicazione in tanti piccoli pezzi, così da renderli
				riutilizzabili, e facilmente manutenibili. <br />
				<br />
				Cosa aspetti? Approfondisci subito!
			</p>
			<Button
				linkDestinazione="https://vuejs.org/v2/guide/components.html"
				msg="Clicca qui!"
			/>
		</div>
		<img src="../assets/components.png" alt="" />
	</div>
</template>

<script>
import Button from "./Button";

export default {
	components: { Button },
	name: "Hero"
};
</script>

<style scoped>
#container {
	position: relative;
	width: 80%;
	margin: auto;
	height: 500px;
}
img {
	position: absolute;
	width: 60%;
	right: 0;
	top: 50%;
	transform: translateY(-50%);
}
#text-container {
	width: 40%;
	height: 100%;
	padding: 60px 30px;
}
p {
	margin-top: 40px;
	font-size: 25px;
	text-align: left;
}
</style>
