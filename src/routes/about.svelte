<section>
	<h2 class="text-divider">About Me</h2>
	<p>
		Hi I'm Sophie. I'm based in the UK and I love travelling and photography. You will find mostly
		landscape photography on my portfolio, however I also have experience in portfolio and wedding
		photography.
	</p>
</section>

<style>
	section {
		height: fit-content;
		background-color: rgb(255, 246, 251);
		padding-top: 20px;
		padding-bottom: 20px;
	}
	h2 {
		margin: 0;
		padding-bottom: 10px;
	}
	p {
		max-width: 50%;
		text-align: center;
		margin: auto;
		/* display: flex;
		justify-content: space-around; */
	}
	.text-divider {
		display: flex;
		align-items: center;
	}

	.text-divider::before,
	.text-divider::after {
		content: '';
		height: 1px;
		background-color: black;
		flex-grow: 1;
	}
</style>
