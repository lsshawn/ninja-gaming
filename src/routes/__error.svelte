<script context="module">
	/** @type {import('@sveltejs/kit').Load} */
	export function load({ error }) {
		return {
			props: { message: error ? error.message : '' }
		};
	}
</script>

<script>
	export let message;
</script>

<div class="error">
	<h2>Ops</h2>
	<p>message</p>
	<a href="/guides" target="_blank">View all guides...</a>
</div>

<style>
	.error {
		text-align: center;
		margin-bottom: 60px;
	}
</style>
