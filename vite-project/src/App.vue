<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'
import AppCard from './components/AppCard.vue'

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
    AppCard
  },
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
      ],

    }
  }
}
</script>

<template>
  <AppHeader :links="menuLinks" />

  <AppMain />
  <AppFooter />
</template>

<style scoped></style>
