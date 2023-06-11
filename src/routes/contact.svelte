<section>
	<h2 class="text-divider">Contact</h2>
</section>

<style>
	section {
		height: fit-content;
		background-color: rgb(246, 249, 255);
		padding-top: 20px;
		padding-bottom: 50px;
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
