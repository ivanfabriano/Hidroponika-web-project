<template>
  <v-footer padless>
    <v-card flat tile class="green darken-1 white--text text-center">
      <v-card-text> </v-card-text>

      <v-row no-gutters align="center">
        <v-col class="catalog-col">
          <img src="@/assets/logo.png" alt="Logo" width="120px" />
          <h2>Hidroponika</h2>
        
          <v-card-text class="white--text px-10">
            Hidroponika is a website for hydroponics smart system. Has a smart
            sensor and it can send the temperature and humidity data sensor to
            this website. The device using internet conection to send a realtime
            data to server in 24 hours everyday.
          </v-card-text></v-col
        >

        <v-col class="catalog-col"><catalog-card /></v-col>
      </v-row>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} —
        <strong>Ivan Fabriano Syahputra</strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>

<script>
import CatalogCard from "@/components/CatalogCard.vue";
export default {
  components: {
    CatalogCard,
  },
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
};
</script>

<style scoped>
.catalog-col {
  padding: 0px;
}
</style>
