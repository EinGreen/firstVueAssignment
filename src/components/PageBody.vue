<template>
    <main>
        <h3>Video: </h3>
        <video-section></video-section>
        <pokemon-iframe></pokemon-iframe>
        <required-div></required-div>
    </main>
</template>

<script>
import VideoSection from "./VideoSection";
import PokemonIframe from "./PokemonIframe";
import RequiredDiv from "./RequiredDiv";

    export default {
        name: "page-body",
        components: {
            VideoSection,
            PokemonIframe,
            RequiredDiv,
        },
    }
</script>

<style scoped>
    main {
        width: 100%;
    }
</style>

