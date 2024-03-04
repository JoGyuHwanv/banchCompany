
<script>
    import Header from '../lib/components/header/Header_main.svelte'
    import Footer from '../lib/components/footer/Footer_main.svelte'
    import '$lib/styles/style.css'
</script>

<Header />

<main>
    <slot />
</main>
