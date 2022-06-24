<script>
	let title = 'Ninja Gaming Guide';
	const updateTitle = () => {
		title = 'Something else';
	};
</script>

<div class="index">
	<h2>{title}</h2>
	<p>
		Elit eum voluptas eligendi at atque, sint? Impedit esse magnam blanditiis
		enim vel nostrum. Esse voluptas ea sit quia iusto sunt inventore vero!
		Praesentium enim ipsa recusandae pariatur sunt Dolorem?
	</p>

	<button on:click={updateTitle}>Change title</button>
	<input type="text" bind:value={title} />

	<a href="/guides">Guides</a>
	<a href="/about">About</a>
</div>

<style>
	.index {
		text-align: center;
		display: block;
		margin: 20px auto;
	}
</style>
