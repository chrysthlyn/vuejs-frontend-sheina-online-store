<template>
  <div class="home">
    <HeaderSheina />
    <HeroSheina />
    <BannerSheina />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSheina from "../components/HeaderSheina.vue";
import HeroSheina from "../components/HeroSheina.vue";
import BannerSheina from "../components/BannerSheina.vue";

export default {
  name: "Home",
  components: {
    HeaderSheina,
    HeroSheina,
    BannerSheina,
  },
};
</script>
