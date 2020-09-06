<template>
  <div id="app">
    <div class="site-wrap">
      <SiteMobileMenu />
      <PodcaHeader />
      <MostRecentPodcast />
      <RecentPodcasts />
      <BehindTheMic />
      <FeaturedGuests />
      <SubscribeBanner />
      <PodcaFooter />
    </div>
  </div>
</template>

<script>
import PodcaFooter from "./components/PodcaFooter.vue";
import SubscribeBanner from "./components/SubscribeBanner.vue";
import FeaturedGuests from "./components/FeaturedGuests.vue";
import BehindTheMic from "./components/BehindTheMic.vue";
import RecentPodcasts from "./components/RecentPodcasts.vue";
import MostRecentPodcast from "./components/MostRecentPodcast.vue";
import PodcaHeader from "./components/PodcaHeader.vue";
import SiteMobileMenu from "./components/SiteMobileMenu.vue";

export default {
  name: "App",
  components: {
    PodcaFooter,
    SubscribeBanner,
    FeaturedGuests,
    BehindTheMic,
    RecentPodcasts,
    MostRecentPodcast,
    PodcaHeader,
    SiteMobileMenu,
  },
};
</script>

<style>
/* Removed for proper podca formatting */
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
