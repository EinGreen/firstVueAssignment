<template>
    <section>
        <h3>News Video: </h3>
        <iframe 
         width="560" 
         height="315" 
         src="https://www.youtube.com/embed/xfr64zoBTAQ"
         title="Fun Video" 
         frameborder="0" 
         allow="accelerometer; 
         autoplay; 
         clipboard-write; 
         encrypted-media; 
         gyroscope; 
         picture-in-picture" 
         allowfullscreen
         alt="Dang it, this was supposed to Rick Roll you, how is this possible?">
            <!-- I added the alt tag just in case the video wants to be mean -->
        </iframe>
        <!-- Ha ha ha, this is a rickroll link -->
    </section>
</template>

<script>
    export default {
        // It's a section that contains an Iframe video from YouTube, what did you expect it's name to be?
        name: "video-section",
    }
</script>

<style scoped>
/* lol, no styling here */
</style>