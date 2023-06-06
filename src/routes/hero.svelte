<script>
	// import heroImg from "./hero.jpg";
	import hero from './hero.jpg';
</script>

<div>
	<img alt="pier at sunset" src={hero} />
	<div class="text">
		<h1>Sophie Earl<br />Photography</h1>
		<br />
	</div>
</div>

<style>
	img {
		/* max-height: 100vh; */
		max-width: 100vw;
	}
	div {
		display: flex;
		flex-direction: column;
		position: relative;
		justify-content: center;
		width: 100%;
	}
	img {
		max-width: 100%;
		height: auto;
	}
	h1 {
		color: white;
		padding-left: 50px;
		font-size: 100px;
		font-weight: lighter;
		font-family: 'Roboto Mono', monospace;
		text-shadow: 1px 1px rgb(76, 76, 76);
		text-transform: uppercase;
		text-align: center;
	}

	.text {
		position: absolute;
	}
	@media screen and (max-width: 500px) {
		div {
			width: 100%;
			height: auto;
		}
		img {
			/* width: 100vh; */
			height: auto;
		}

		.text {
			max-width: 100vw;
		}

		h1 {
			font-size: xx-large;
			padding: 0;
		}
		/* p {
			padding: 0;
			font-size: small;
		} */
	}

	@media screen and (max-width: 950px) {
		div {
			width: 100%;
			height: auto;
		}
		img {
			/* width: 100vh; */
			height: auto;
		}

		/* .hours {
			transform: none;
			color: rgb(255, 255, 255);
			position: static;
		} */
		.text {
			max-width: 100vw;
		}

		h1 {
			font-size: xx-large;
			padding: 0;
		}
		/* p {
			padding: 0;
			font-size: small;
		} */
	}
</style>
