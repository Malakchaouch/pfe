<script>
    import "../app.pcss";
    import Header from "../lib/Components/header.svelte";
    import Footer from "../lib/Components/footer.svelte";
</script>
<section class="flex">
    <Header/>
    
    <div class="ml-20">
        <slot/>
    </div>
    <Footer/>
</section>