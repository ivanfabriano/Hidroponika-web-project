<template>
  <v-app-bar
    color="transparent"
    elevate-on-scroll
    scroll-target="#scrolling-techniques-7"
    fixed
    rounded-pill
  >
  
    <v-app-bar-nav-icon none class="nav-brand"><img src="@/assets/logo.png" alt="Logo" width="50px"/></v-app-bar-nav-icon>

    <v-toolbar-title class="nav-brand"><span><a href="#">Hidroponika</a>
        </span></v-toolbar-title>

    <v-spacer></v-spacer>

    <a class="nav-top nav-link" href="#">Home</a>

    <a class="nav-top nav-link" href="#">About Us</a>

    <a class="nav-top nav-link" href="#">Services</a>

    <a class="nav-top nav-link" href="#">
      <div class="my-2">
        <v-btn rounded color="warning" dark>
          Get Started
        </v-btn>
      </div></a
    >
  </v-app-bar>
</template>

<style scoped>
.nav-top {
  margin-top: 50px;
}
.nav-link {
  color: white;
  font-weight: 400;
  margin-right: 3rem;
  margin-left: 3.3rem;
  text-decoration: none;
  font-size: 1.2rem;
}
.button-text {
  font-weight: 400;
}
.nav-brand{
    margin-top: 50px;
    padding-left: 60px;
}
.nav-brand > span > a{
    font-weight: 600;
    font-size: 1.6rem;
    color: white;
    padding-left: 20px;
    text-decoration: none;
}
</style>
