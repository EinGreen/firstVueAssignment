<template>
    <main>
        <video-section></video-section>
        <pokemon-iframe></pokemon-iframe>
        <required-div></required-div>
        <!-- Note: think of the sub-components like normal divs/sections on an html page, only now, they have their own file -->
    </main>
</template>

<script>
// Imports from sub-components, and this component is connected to App.vue
// Note: Iframes from YouTube work as expected
import VideoSection from "./VideoSection";
// Note: PokemonIframe very weird and buggy
import PokemonIframe from "./PokemonIframe";
import RequiredDiv from "./RequiredDiv";

    export default {
        name: "page-body",
        // The names of the sub-components connected to PageBody
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

