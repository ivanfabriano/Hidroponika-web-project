<template>
  <div class="main">
    <header-content />
    <div class="content">
      <v-container fluid class="content-container">
        <v-row class="first-row">
          <div class="first-caption">
            <h2>Make your hydroponic garden undercontrol</h2>
            <p>
              Don't have much time to control your hydroponic garden directly?,
              Let's try us, you can monitoring your garden easily and anywhere.
            </p>
          </div>
        </v-row>
        <v-row class="features-row">
          <v-col class="features-col"
            ><img src="../assets/realtime.png" alt="Realtime" />
            <p>Realtime Data Monitoring</p></v-col
          >
          <v-col class="features-col"
            ><img src="../assets/history.png" alt="History" />
            <p>Data History Collecting</p></v-col
          >
          <v-col class="features-col"
            ><img src="../assets/devices.png" alt="Devices" />
            <p>Integrated Sensor Device</p></v-col
          >
        </v-row>
        <v-row class="third-row">
          <div class="third-caption">
            <h2>Yes, we are smart hydroponic garden systems</h2>
            <p>
              be curious? scroll down for more detailed information.
            </p>
          </div>
        </v-row>
      </v-container>
    </div>
    <feature-content/>
    <div></div>
    <footer-bar/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderContent from "@/components/HeaderContent.vue";
import FeatureContent from "@/components/FeatureContent.vue";
import FooterBar from "@/components/FooterBar.vue";

export default {
  name: "Home",
  components: {
    HeaderContent,
    FeatureContent,
    FooterBar,
  },
};
</script>
<style>
#app {
  background-image: url("../assets/bg.png");
  background-repeat: no-repeat;
  background-size: 100vmax 40vmax;
  background-position: top left;
}

.content {
  margin-top: 17rem;
}
.first-row {
  justify-content: center;
}
.first-row .first-caption {
  margin-bottom: 30px;
  width: 35rem;
  height: auto;
}
.first-caption > h2 {
  font-weight: 600;
  font-size: 2rem;
  margin-bottom: 7px;
}
.first-caption > p {
  font-weight: 300;
}
.features-row {
  margin-top: 17rem;
  background-color: #269c34;
  padding: 50px;
  margin: 0;
}
.features-col > p {
  color: #fdffff;
  margin-top: 30px;
  font-weight: 600;
}
.third-row {
  justify-content: center;
}
.third-row .third-caption {
  margin-bottom: 30px;
  width: 35rem;
  height: auto;
}
.third-caption > h2 {
  font-weight: 600;
  font-size: 2rem;
  margin-bottom: 7px;
  margin-top: 200px;
}
.third-caption > p {
  font-weight: 300;
}
@media screen and (max-width: 600px) {
  #app{
    background-size: 100vmax 50vmax;
  }
  .features-col {
    margin: 10px 10px;
  }
  .content{
    margin-top: 10rem
  }
}
</style>
