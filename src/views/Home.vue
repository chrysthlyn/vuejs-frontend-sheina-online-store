<template>
  <div class="home">
    <HeaderSheina />
    <HeroSheina />
    <BannerSheina />
    <InstaSheina />
    <PartnerSheina />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSheina from "../components/HeaderSheina.vue";
import HeroSheina from "../components/HeroSheina.vue";
import BannerSheina from "../components/BannerSheina.vue";
import InstaSheina from "../components/InstaSheina.vue";
import PartnerSheina from "../components/PartnerSheina.vue";

export default {
  name: "Home",
  components: {
    HeaderSheina,
    HeroSheina,
    BannerSheina,
    InstaSheina,
    PartnerSheina,
  },
};
</script>
