<template>
  <div class="main-container">
    <div class="container">
      <div class="image-stack">
        <div class="image-stack__item image-stack__item--top">
          <div class="mini-container1">
            <h2>Realtime Monitoring</h2>
            <p>
              Hidroponika can monitor your gardens for 24 hours. By using an
              internet connection, temperature data and humidity data will be
              reported in real time.
            </p>
            <div class="my-2">
              <v-btn large rounded color="#00E676" dark>
                Preview
              </v-btn>
            </div>
          </div>
        </div>
        <div class="image-stack__item image-stack__item--bottom">
          <img src="@/assets/ftbg1.png" alt="" />
        </div>
      </div>
    </div>
    <div class="container">
      <div class="image-stack">
        <div class="image-stack__item image-stack__item--top">
          <div class="mini-container2">
            <h2>Data History Collecting</h2>
            <p>
              Hidroponika will store data history every day so that it can be
              used for analysis and improve your strategy for better future.
            </p>
            <div class="my-2">
              <v-btn large rounded color="#00E676" dark>
                Preview
              </v-btn>
            </div>
          </div>
        </div>
        <div class="image-stack__item image-stack__item--bottom">
          <img src="@/assets/ftbg2.png" alt="" />
        </div>
      </div>
    </div>
    <div class="container">
      <div class="image-stack">
        <div class="image-stack__item image-stack__item--top">
          <div class="mini-container3">
            <h2>Integrated Sensor Devices</h2>
            <p>
              Hidroponika has an intregated sensor device with temperatue sensor
              and humidity sensor to monitor your garden.
            </p>
            <div class="my-2">
              <v-btn large rounded color="#00E676" dark>
                Preview
              </v-btn>
            </div>
          </div>
        </div>
        <div class="image-stack__item image-stack__item--bottom">
          <img src="@/assets/ftbg3.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
* {
  box-sizing: border-box;
}

p {
  font-size: 20px;
  font-family: sans-serif;
  color: #6439a9;
}

.container {
  padding: 15px 30px;
  width: 100%;
  margin: 0 auto;
  max-width: 900px;
  margin-bottom: 10vmax;
}

.image-stack {
  display: grid;
  position: relative;
  grid-template-columns: repeat(12, 1fr);
}

.image-stack__item--bottom {
  grid-column: 4 / -1;
  grid-row: 1;
}

.image-stack__item--top {
  grid-row: 1;
  grid-column: 1 / span 8;
  padding-top: 20%;
  z-index: 1;
}

img {
  width: 100%;
  display: block;
}
.mini-container1 {
  width: 30vmax;
  height: 30vmax;
  background-color: #03a9f4;
  display: block;
  padding: 2vmax 2vmax;
}
.mini-container2 {
  width: 30vmax;
  height: 30vmax;
  background-color: #ff9800;
  display: block;
  padding: 2vmax 2vmax;
}
.mini-container3 {
  width: 30vmax;
  height: 30vmax;
  background-color: #e91e63;
  display: block;
  padding: 2vmax 2vmax;
}
.mini-container1 > h2 {
  font-weight: 700;
  font-size: 2.3vmax;
  color: white;
  margin-bottom: 1.7vmax;
}
.mini-container1 > p {
  font-weight: 400;
  font-size: 1.7vmax;
  color: white;
  margin-bottom: 1.7vmax;
}
.mini-container2 > h2 {
  font-weight: 700;
  font-size: 2.3vmax;
  color: white;
  margin-bottom: 1.7vmax;
}
.mini-container2 > p {
  font-weight: 400;
  font-size: 1.7vmax;
  color: white;
  margin-bottom: 1.7vmax;
}
.mini-container3 > h2 {
  font-weight: 700;
  font-size: 2.3vmax;
  color: white;
  margin-bottom: 1.7vmax;
}
.mini-container3 > p {
  font-weight: 400;
  font-size: 1.7vmax;
  color: white;
  margin-bottom: 1.7vmax;
}

@media screen and (max-width: 600px) {
}
</style>
