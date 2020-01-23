<template>
    <div class="text-section" v-editable="blok">
        <h1 class="title"> {{ blok.title }} </h1>
        <div class="body">
            {{ blok.body }}
        </div>
    </div>
</template>

<script>
    export default {
        name: "TextSection",
        props: ['blok']
    }
</script>

<style scoped lang="scss">
    .text-section {
        margin: 0 auto;
        max-width: 500px;
        box-shadow: 0px 1px 10px 0px #ccc;
        border: 1px solid #ddd;
        padding: 20px;

        .body {
            color: grey;
        }
    }
</style>