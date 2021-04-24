<template>
    <div>
        <h4>Meet the Team:</h4>
        <section id="credits">
            <div class="workerCard">
                <h6>Designer: </h6>
                <p>Mal</p>
            </div>
            <div class="workerCard">
                <h6>Editor: </h6>
                <p>Mal</p>
            </div>
            <div class="workerCard">
                <h6>Director: </h6>
                <p>Mal</p>
            </div>
            <div class="workerCard">
                <h6>Programers: </h6>
                <p>Me</p>
                <p>Myself</p>
                <p>Mal</p>
            </div>
            <div class="workerCard">
                <h6>Marketing Team: </h6>
                <p>Mal</p>
                <p>Mal</p>
                <p>Mal</p>
            </div>
            <div class="workerCard">
                <h6>Pro Gamer [not really]: </h6>
                <p>Mal</p>
            </div>
            <div class="workerCard">
                <h6>Pain and Suffering: </h6>
                <p>Mal</p>
            </div>
        </section>
    </div>
</template>

<script>
    export default {
        // I named it this because I didn't know if the other sub-components were acceptable
        name: "required-div",
    }
</script>

<style scoped>
/* bit rusty with css styling, but I think I managed */
    #credits {
        display: grid;
        gap: 15px;
        grid-auto-columns: 1fr;
    };

    .workerCard {
        border-style: solid;
        border-width: medium;
    }

</style>