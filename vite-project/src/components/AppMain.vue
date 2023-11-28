<script>
export default {
    name: "AppHeader",
    data() {
        return {
            menuLinks: [
                {
                    src: "",
                },
                {
                    text: "comics",
                },
                {
                    text: "movies",
                },
                {
                    text: "tv",
                },
                {
                    text: "tv",
                },
            ]
        }
    },
    mounted() {
        console.log("Componente AppHeader caricato");
    }
}
</script>

<template>
    <main>
        <div class="content">
            <div>content goes here</div>
        </div>
        <div class="content2">
            <a v-for="gadget in gadgets" :href="link.url">{{ gadget.text }}</a>
        </div>
    </main>
</template>

<style scoped>
.content {
    height: 10rem;
    background-color: black;
    color: white;
    display: flex;
    align-items: center;
}
</style>