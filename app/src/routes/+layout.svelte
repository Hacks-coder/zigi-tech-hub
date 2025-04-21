<script lang="ts">
	import '../app.css';
	import Header from '../components/Header/Header.svelte';

	let { children } = $props();
</script>


<div class="@container">
	<div class="text-sm @xl:text-lg">
		<Header />
		{@render children()}
	</div>
</div>