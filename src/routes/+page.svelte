<script>
	import { Button } from '$lib/components/ui/button';

	let count1 = $state(0);

	let count = 0;
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<Button on:click={() => count++}>Click me +</Button>
<Button on:click={() => count--}>Click me -</Button>

{count}
