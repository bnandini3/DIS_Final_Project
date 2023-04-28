<script>
    import "../app.css";
    import CopyRight from "../components/CopyRight.svelte";
    import Navbar from "../components/Navbar.svelte";



</script>
<div class="color" >
<div class="min-h-screen">
    <Navbar />
    <slot />
</div>
<CopyRight />
</div>

<style>
    .color{
        background-color: rgb(187, 190, 191);
    }
</style>