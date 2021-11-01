<template>
  <div class="home">
    <HeaderSheina />
    <HeroSheina />
    <BannerSheina />
    <InstaSheina />
    <PartnerSheina />
    <FooterSheina />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSheina from "../components/HeaderSheina.vue";
import HeroSheina from "../components/HeroSheina.vue";
import BannerSheina from "../components/BannerSheina.vue";
import InstaSheina from "../components/InstaSheina.vue";
import PartnerSheina from "../components/PartnerSheina.vue";
import FooterSheina from "../components/FooterSheina.vue";

export default {
  name: "Home",
  components: {
    HeaderSheina,
    HeroSheina,
    BannerSheina,
    InstaSheina,
    PartnerSheina,
    FooterSheina,
  },
};
</script>
