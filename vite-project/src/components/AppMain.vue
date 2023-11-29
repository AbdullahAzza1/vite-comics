<script>
export default {
    name: "AppHeader",
    data() {
        return {
            gadgets: [
                {
                    src: "/img/buy-comics-digital-comics.png",
                    text: "digital comics"
                },
                {
                    src: "/img/buy-comics-merchandise.png",
                    text: "dc merchandise"
                },
                {
                    src: "/buy-comics-shop-locator.png",
                    text: "subscription"
                },
                {
                    src: "/img/buy-comics-subscriptions.png",
                    text: "comic shop locator"
                },
                {
                    src: "/img/buy-comics-subscriptions.png",
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
            <img :src="getImagePath(gadgets)" />
            <a v-for="gadget in gadgets" :href="gadget.url" :src="getImagePath(gadgets.src)">{{ gadget.text }}</a>
        </div>
    </main>
</template>

<style scoped>
.content {
    height: 10rem;
    background-color: rgb(10, 6, 79);
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