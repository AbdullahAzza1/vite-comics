<script>
export default {
    name: "AppMain",
    props: ["image", "titolo"]
}
</script>

<template>
    <div id="card">
        <img :src="image" alt="">
        <p> {{ titolo }} </p>
    </div>
</template>

<style>
#card {
    width: calc(100%/6 - 2rem);
    margin: 1rem;
}
</style>