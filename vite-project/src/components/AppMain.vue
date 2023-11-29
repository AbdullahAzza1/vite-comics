<script>
export default {
    name: "AppHeader",
    data() {
        return {
            gadgets: [
                {
                    src: "/public/img/buy-comics-digital-comics.png",
                    text: "digital comics"
                },
                {
                    src: "vite-project/src/assets/img/buy-comics-merchandise.png",
                    text: "dc merchandise"
                },
                {
                    src: "vite-project/src/assets/img/buy-comics-shop-locator.png",
                    text: "subscription"
                },
                {
                    src: "vite-project/src/assets/img/buy-comics-subscriptions.png",
                    text: "comic shop locator"
                },
                {
                    src: "vite-project/src/assets/img/buy-comics-subscriptions.png",
                    text: "dc power visa"
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
            <a v-for="gadget in gadgets" :href="gadget.url">{{ gadget.src }} {{ gadget.text }}</a>
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

.content2 {
    height: 13rem;
    background-color: rgb(34, 78, 111);
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>