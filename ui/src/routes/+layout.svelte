<script>
	import './styles.css';
	import Sidebar from "./Sidebar.svelte";
</script>

<div class="app d-flex flex-nowrap align-items-stretch">
	<Sidebar />

	<main class="flex-grow-1 p-3">
		<slot />

		<footer class="flex-fill">
			<p>Copyright ..</p>
		</footer>
	</main>
</div>

<style>

</style>
