<script>
    import Header from "./Header.svelte";

    let name = $state('Mike');
</script>

<Header {name}/>

<input type="text" bind:value={name} />

