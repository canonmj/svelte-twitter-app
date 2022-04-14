<script>
	export let error;
</script>

{#if error}
	<p class="text-red-600">{error.message}</p>
{/if}
