<template>
  <v-container fluid class="main">
    <v-row no-gutters class="main-row">
      <v-col cols="12" sm="12" md="6" class="header">
        <h1>Hidroponika</h1>
        <p>Make Our Smart Hidroponic Garden</p>
      </v-col>
      <v-col md="6" class="description">
        <v-carousel
          class="carousel"
          cycle
          height="400"
          hide-delimiter-background
          show-arrows-on-hover
        >
          <v-carousel-item v-for="(slide, i) in slides" :key="i">
            <v-sheet :color="colors[i]" height="100%">
              <v-row class="fill-height" align="center" justify="center">
                <div class="display-3">
                  {{ slide }} Slide
                  <p :caption="caption">{{ caption[i] }}</p>
                </div>
              </v-row>
            </v-sheet>
          </v-carousel-item>
        </v-carousel>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
export default {
  data() {
    return {
      colors: ["transparent", "transparent", "transparent"],
      slides: ["First", "Second", "Third"],
      caption: ["Get Simpler Method", "Second", "Third"],
    };
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@200;300;400;600;700&display=swap");
.main {
  font-family: "Montserrat", sans-serif;
  margin: 0;
}
.main-row {
}
.header {
  margin-top: 15vmax;
  text-align: center;
  justify-content: center;
}
.header > h1 {
  color: #fdffff;
  font-weight: 600;
  font-size: 4em;
}
.header > p {
  color: #fdffff;
  font-weight: 400;
  margin-top: -10px;
}
.description {
  margin-top: 15vmax;
  text-align: center;
  justify-content: center;
}
.carousel {
}
.display-3 {
  color: black;
}
.display-4 {
  color: black;
}

@media screen and (max-width: 600px) {
  .header > h1 {
    color: #fdffff;
    font-weight: 600;
    font-size: 2em;
  }
}
</style>
