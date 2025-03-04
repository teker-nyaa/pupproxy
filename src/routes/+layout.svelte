<script>
	import '../app.css';
	let { children } = $props();
</script>

<div id="header">
	<h1 class="text-2xl font-medium text-rose-300">PupProxy</h1>
</div>

{@render children()}
