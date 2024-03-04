<script>
    import { fade, blur, fly, slide, scale, draw } from 'svelte/transition';
</script>
<h1 in:fade="{{delay: 1000}}" out:fade="{{duration: 1000}}">phone</h1>