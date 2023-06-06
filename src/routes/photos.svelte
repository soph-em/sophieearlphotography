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
		</li>
		<li>
			<img alt="view over bath city" src={bath} />
		</li>
		<!-- </div> -->
		<li>
			<img alt="view of sennen cove" src={cornwall} />
		</li>
		<li class="bigger">
			<img alt="macro of white flower" src={flower} />
		</li>
		<li class="bigger">
			<img alt="a bridge lit blue at dusk" src={newcastle} />
		</li>
		<li>
			<img alt="people running up a hill toward a monument" src={penshaw} />
		</li>
		<li>
			<img alt="view of old tin mines" src={sennen} />
		</li>
		<li class="bigger">
			<img alt="5 people between pillars sihouetted on a landscape" src={silhouette} />
		</li>
		<li class="bigger">
			<img alt="snowy landscape" src={snow} />
		</li>
		<li class="bigger">
			<img alt="view of a harbour" src={harbour} />
		</li>
	</ul>
</section>

<style>
	.bigger {
		height: 60vh !important;
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
</style>
