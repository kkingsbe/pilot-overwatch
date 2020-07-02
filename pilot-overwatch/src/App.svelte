<script>
	export let name;
	import BackgroundImage from './components/BackgroundImage.svelte'
	import SignInModal from './components/SignInModal.svelte'
</script>

<main>
	<BackgroundImage src="../res/background.jpg"/>
	<div class="container">
		<SignInModal></SignInModal>
	</div>
</main>

<style>
	main {
		text-align: center;
		margin: 0 auto;
		height: 100%;
		width: 100%;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	.container {
		min-height: 100%;
		width: 100%;
		position: absolute;
		left: 0;
		top: 0;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>