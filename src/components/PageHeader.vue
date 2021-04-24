<template>
    <header id="pageHeader">
        <h2>Insert Fancy Header that has no meaning cause points for style aren't awarded in this assignment!</h2>
        <!-- wow, what a very meaningful Header! -->
        <nav>
            Note: Links lead to nowhere
            <a href="#">About Us</a>
            <a href="#">Contact</a>
            <a href="#">Job Offers [there are non]</a>
            <a href="#">Dank Memes</a>
        </nav>
    </header>
</template>

<script>
export default {
    // wow, what a creative name
    name: "page-header",
}
</script>

<style scoped>
    header {
        display: grid;
        place-items: center;
        grid-auto-flow: column;
    }

    a {
        padding: 10px;
    }
</style>