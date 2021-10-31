<template>
  <div class="home">
    <HeaderSheina />
    <HeroSheina />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSheina from "../components/HeaderSheina.vue";
import HeroSheina from "../components/HeroSheina.vue";

export default {
  name: "Home",
  components: {
    HeaderSheina,
    HeroSheina,
  },
};
</script>
