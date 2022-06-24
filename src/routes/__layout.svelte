<script>
	import Title from '$lib/title.svelte';
	import '../styles/global.scss';
</script>

<header>
	<Title title="Ninja Gaming Guides" />
</header>

<main>
	<!-- page content -->
	<slot />
</main>

<footer>
	<p>Copyright</p>
</footer>

<style>
	header {
		display: flex;
		justify-content: center;
	}
	main {
		max-width: 960px;
		margin: 20px auto;
	}
	footer {
		text-align: center;
	}
</style>
