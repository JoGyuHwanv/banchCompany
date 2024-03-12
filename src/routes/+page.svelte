<script>
    import { fade, blur, fly, slide, scale, draw } from 'svelte/transition';
</script>

<h1 in:fade="{{delay: 1000}}" out:fade="{{duration: 1000}}">Welcome to SvelteKit</h1>
<p in:fade="{{delay: 1000}}" out:fade="{{duration: 1000}}">Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
