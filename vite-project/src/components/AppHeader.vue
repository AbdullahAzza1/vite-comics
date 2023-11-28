<script>
export default {
    name: "AppHeader",
    data() {
        return {
            menuLinks: [
                {
                    text: "characters",
                    url: "#characters",
                },
                {
                    text: "comics",
                    url: "#comics",
                },
                {
                    text: "movies",
                    url: "#movies",
                },
                {
                    text: "tv",
                    url: "#tv",
                },
                {
                    text: "games",
                    url: "#games",
                },
                {
                    text: "collectibles",
                    url: "#collectibles",
                },
                {
                    text: "videos",
                    url: "#videos",
                },
                {
                    text: "fans",
                    url: "#fans",
                },
                {
                    text: "news",
                    url: "#news",
                },
                {
                    text: "shop",
                    url: "#shop",
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
    <header>
        <nav>
            <img src="../assets/img/dc-logo.png" alt="">
            <div>
                <a v-for="link in menuLinks" :href="link.url">{{ link.text }}</a>
            </div>
        </nav>
    </header>
</template>

<style scoped>
header {
    height: 9rem;
}

nav a {
    margin: 0 1rem;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
}
</style>
