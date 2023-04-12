<script>

export default {
    name: "AppTitle",
    data(){
        return {
            text: "La mia prima app con Vite!"
        }
    },
}

</script>

<template>

    <p> {{ text }}</p>

</template>

<style>
p {
    color: red;
    font-size: 30px;
}

</style>
