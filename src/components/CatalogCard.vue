<template>
  <v-card :loading="loading" class="mx-auto my-12 catalog-card">
    <template slot="progress">
      <v-progress-linear
        color="white"
        height="10"
        indeterminate
      ></v-progress-linear>
    </template>
    <h2>Discount Packet</h2>
    <v-img
      height="150"
      src="https://cdn.vuetifyjs.com/images/cards/cooking.png"
    ></v-img>

    <v-card-title>First Members</v-card-title>

    <v-card-text>
      <div class="text-left pl-2">
        <p>1. Integrated smart devices (permanent)</p>
        <p>2. Free trial 3 Months</p>
        <p>3. Discount voucher for next session</p>
        <p>4. Hydroponics master mentoring</p>
      </div>
    </v-card-text>

    <v-divider class="mx-4"></v-divider>

    <v-card-title class="justify-center pb-0"
      >Discount Until 23/8/21</v-card-title
    >

    <v-card-actions class="justify-center pb-4">
      <v-btn rounded color="warning" dark>
        Get Packet
      </v-btn>
    </v-card-actions>
  </v-card>
</template>

<style scoped>
.catalog-card {
  max-width: 374px;
}
@media screen and (max-width: 600px) {
  .catalog-card {
    max-width: 300px;
  }
}
</style>
