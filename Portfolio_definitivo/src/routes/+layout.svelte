<script>
    import Nav from "../lib/components/nav.svelte";
    import './style.css';
</script>

<header>
    <Nav />
</header>

<article>
    <slot></slot>
</article>