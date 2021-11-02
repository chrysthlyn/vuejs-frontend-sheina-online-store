<template>
  <div class="product">
    <HeaderSheina />
    <FooterSheina />
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderSheina from "../components/HeaderSheina.vue";
import FooterSheina from "../components/FooterSheina.vue";

export default {
  name: "Product",
  components: {
    HeaderSheina,
    FooterSheina,
  },
};
</script>
