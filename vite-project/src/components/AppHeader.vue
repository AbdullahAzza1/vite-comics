<script>
export default {
    name: "AppHeader",
    props: ["links"],
    data() {
        return {
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
            <img src="/img/dc-logo.png" alt="">
            <div>
                <a v-for="link in links" :href="link.url">{{ link.text }}</a>
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
