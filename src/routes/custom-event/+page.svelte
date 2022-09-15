<script>
	import EventButton from "$lib/EventButton.svelte";

</script>
<svelte:head>
	<title>Custom Event</title>
	<meta name="description" content="Custom Event Testing Area" />
</svelte:head>

<div class="content">
	<h1>Testing Area for Custom Events</h1>

    <button>Click Me</button>

    <EventButton />
</div>

<style>
	.content {
		width: 100%;
		max-width: var(--column-width);
		margin: var(--column-margin-top) auto 0 auto;
	}
</style>
