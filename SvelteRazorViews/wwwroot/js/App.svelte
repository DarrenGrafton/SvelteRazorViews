<svelte:options tag="svelte-app" />
<script>
    export let name;
    export let id;
</script>

<main>
    <h1 id="{id}">Hello {name}!</h1>
	<p>how are you doing?</p>
	<p>Just fine....</p>
</main>

<style>
    h1 {
        font-size: 5em;
		color: green;
		margin-bottom: 0;
    }
</style>
