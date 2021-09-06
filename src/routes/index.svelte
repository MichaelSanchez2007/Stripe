<script>
	import Header from '$lib/Header.svelte';

	function close() {
		window.close();
		alert(SIKE);
	}
</script>

<Header />

<div class="hero-background" />

<section class="section-1">
	<div class="Title">
		<h2>Want a third camera for 2k?</h2>
		<hr />
		<p>
			Nam id luctus elit, eget ultricies augue. Maecenas efficitur metus ut est aliquet elementum.
			Fusce molestie molestie turpis, non facilisis odio ullamcorper eu. Vivamus a tincidunt felis.
		</p>
		<button on:click={close}>CLICK TO SEE FUTURE</button>
	</div>
</section>

<div class="overlay" />

<section class="section-2">
	<h1>Why Apple?</h1>
	<div class="holder" />
	<div class="second">
		<b> This is all you mortals need to conceive to undertand why Apple is on TOP. </b>
		<br />
		<br />
		<br />
		<br />
		<li>This is all a joke apple is hella good</li>
		<br />
		<li>We are all about looks. Functionality who?</li>
		<br />
		<li>"Yo, nice phone. What it do?" Nothing</li>
		<br />
		<li>lmao get scammed</li>
		<br />
		<li>We just put a sticker the camera doesn't even work</li>
		<br />
		<li>Golden hour!!!!</li>
		<br />
		<li>Accomplish nothing</li>
		<br />
		<li>Lose all money</li>
	</div>
</section>

<style>
	h1 {
		text-align: center;
		transform: rotate(16deg);
		width: 300px;
		height: 10px;
		position: relative;
		margin-left: 310px;
		font-size: 40px;
	}
	li {
		padding: 5px;
		text-align: center;
	}
	b {
		text-align: center;
		margin: auto;
		padding: 120px;
		width: 200px;
		height: 100px;
	}
	.second {
		background: rgb(255, 255, 255);
		width: 800px;
		height: 450px;
		border-radius: 25px;
		position: absolute;
		margin-left: 1000px;
		top: -150px;
	}
	.holder {
		background: white;
		width: 450px;
		height: 100px;
		margin: auto;
		border-radius: 25px;
		position: absolute;
		margin-left: 1000px;
		bottom: 1000px;
	}
	h3 {
		background: rgb(231, 201, 201);
		width: 200px;
		height: 50px;
		border-radius: 25px;
		text-align: center;
	}

	.container {
		background: rgb(185, 185, 194);
		width: 500px;
		height: 700px;
		border-radius: 50px;
		position: absolute;
		margin-left: 1100px;
		bottom: 400px;
		filter: opacity(1);
	}
	button {
		background: black;
		color: white;
		padding: 0.5rem 1rem;
		border-radius: 25px;
		font-size: 1rem;
		font-weight: 500;
		outline: none;
		border: none;
		font-family: 'Questrial', sans-serif;
	}
	hr {
		width: 400px;
		left: 0;
		border: 1px solid white;
		margin: 0;
		margin-top: 10px;
		margin-left: 7.5rem;
	}
	h2 {
		font-size: 100px;
		color: white;
		margin: auto;
	}
	p {
		max-width: 700px;
		letter-spacing: 2px;
		color: white;
	}
	.Title {
		max-width: 850px;
		height: max-content;
		margin-left: min(200px, 5vw);
		padding: 40px;
		padding-top: 200px;
	}
	@media only screen and (max-width: 1000px) {
		.Title {
			margin: auto;
			max-width: 100vw;
			width: 500px;
		}
		h2 {
			font-size: 70px;
		}
		hr {
			margin-left: 2rem;
		}
	}
	.hero-background {
		background-image: url('/Phone.jpg');
		background-size: cover;
		background-repeat: no-repeat;
		position: fixed;
		width: 100vw;
		height: 70vw;
	}
	.section-1 {
		position: relative;
		height: 100vh;
	}
	.overlay {
		width: 150vw;
		height: 100vh;
		background: white;
		position: absolute;
		top: 35rem;
		transform: rotate(-10deg) translateX(-10vw);
		box-shadow: -24px -24px 24px -20px rgba(0, 0, 0, 0.25);
	}
	.section-2 {
		background-image: url('/Phones.png');
		max-width: 800px;
		height: 850px;
		z-index: 11;
		position: relative;
		background-size: cover;
	}
</style>
