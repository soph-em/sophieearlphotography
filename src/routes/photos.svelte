<script>
	import bath from './bath.jpg';
	import harbour from './conrwall harbour.jpg';
	import cornwall from './cornwall.jpg';
	import flower from './flower.jpg';
	import newcastle from './newcastle.jpg';
	import penshaw from './penshaw.jpg';
	import poppies from './poppies.jpg';
	import sennen from './sennen.jpg';
	import silhouette from './silhouette.jpg';
	import snow from './snow.jpg';
</script>

<section>
	<ul>
		<!-- <div class="lineOne"> -->
		<li>
			<img alt="poppies" src={poppies} />
			<div class="hidden">A field of Poppies, County Durham</div>
		</li>
		<li>
			<img alt="view over bath city" src={bath} />
			<div class="hidden">A view over Bath City</div>
		</li>
		<!-- </div> -->
		<li>
			<img alt="view of cornwall" src={cornwall} />
			<div class="hidden">Tin mines on the Cornish Coast</div>
		</li>
		<li class="bigger">
			<img alt="macro of white flower" src={flower} />
			<div class="hidden">Cape Marguerite Daisy</div>
		</li>
		<li class="bigger">
			<img alt="a bridge lit blue at dusk" src={newcastle} />
			<div class="hidden">Millennium Bridge, Newcaslte</div>
		</li>
		<li>
			<img alt="people running up a hill toward a monument" src={penshaw} />
			<div class="hidden">Penshaw Monument, Sunderland</div>
		</li>
		<li>
			<img alt="view of sennen cove" src={sennen} />
			<div class="hidden">View over Sennen Cove</div>
		</li>
		<li class="bigger">
			<img alt="5 people between pillars sihouetted on a landscape" src={silhouette} />
			<div class="hidden">Penshaw Monument, Sunderland</div>
		</li>
		<li class="bigger">
			<img alt="snowy landscape" src={snow} />
			<div class="hidden">Snowy landscape, County Durham</div>
		</li>
		<li class="bigger">
			<img alt="view of a harbour" src={harbour} />
			<div class="hidden">Cornish Harbour</div>
		</li>
	</ul>
</section>

<style>
	div {
		font-family: 'Roboto Mono', monospace;
		position: absolute;
		font-size: x-large;
	}
	.hidden {
		/* visibility: hidden; */
		position: absolute;
		text-align: center;

		top: 0;
		bottom: 0;
		left: 0;
		right: 0;
		background: rgba(32, 32, 33, 0.72);
		color: #ffffff;
		/* visibility: hidden; */
		opacity: 0;
		padding: 0;
		margin: auto;
		padding-top: 30px;

		transition: opacity 0.2s, visibility 0.2s;
	}
	li:hover .hidden {
		visibility: visible;
		opacity: 1;
	}

	img:hover {
		opacity: 1;
		filter: brightness(10%);
		transition: opacity 0.2s, visibility 0.2s;
		transform: scale(1.04);
	}
	.bigger {
		height: 60vh;
	}
	ul {
		display: flex;
		flex-wrap: wrap;
		padding: 0;
	}

	li {
		height: 50vh;
		flex-grow: 1;
		list-style: none;
		padding: 3px;
		position: relative;
	}
	li:last-child {
		flex-grow: 10;
	}
	img {
		max-height: 100%;
		min-width: 100%;
		object-fit: cover;
		vertical-align: bottom;
	}

	@media screen and (max-width: 500px) {
		li {
			max-width: vw;
			height: auto;
		}
		img {
			max-width: 100vw;
		}
		.bigger {
			max-width: vw;
			height: auto;
		}
		div {
			font-size: medium;
		}
	}
	@media (max-width: 1000px) {
		li {
			width: 100vw;
			height: auto;
		}
		img {
			width: 100vw;
			height: auto;
		}
		.bigger {
			max-width: 100vw;
			height: auto;
		}
		div {
			font-size: medium;
			/* color: red; */
		}
	}
</style>
