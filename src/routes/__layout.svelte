<script lang="ts">
  //https://kit.svelte.dev/docs#layouts
	import '../app.css';
</script>

<main>
	<slot />
</main>

<footer>
  <p>Built using <a href="https://kit.svelte.dev/" target="_blank" rel="noopener noreferrer">Svelte Kit</a></p>
  <p>Github Repo: <a href="https://github.com/harryli0088/interactive-visual-uncertainty-quantification" target="_blank" rel="noopener noreferrer">https://github.com/harryli0088/interactive-visual-uncertainty-quantification</a></p>
  <p>Icons provided by Font Awesome: <a href="https://fontawesome.com/license" target="_blank" rel="noopener noreferrer">https://fontawesome.com/license</a></p>
</footer>

<style>
  footer {
		padding: 1em;
	}
	@media only screen and (min-width: 600px) {
		footer {
			padding-left: var(--tablet-padding);
			padding-right: var(--tablet-padding);
		}
	}
	@media only screen and (min-width: 1000px) {
		footer {
			padding-left: var(--desktop-padding);
			padding-right: var(--desktop-padding);
		}
	}

	footer {
		background-color: #ddd;
	}
</style>
