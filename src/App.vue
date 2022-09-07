<template>
  <div id="app">
    <app-navigationBar></app-navigationBar>
    <app-header></app-header>
    <app-about></app-about>
    <app-features></app-features>
    <app-tours></app-tours>
    <app-stories></app-stories>
    <app-booking></app-booking>
    <app-footer></app-footer>
    <app-popup></app-popup>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import About from "./components/About.vue";
import Features from "./components/Features.vue";
import Tours from "./components/Tours.vue";
import Stories from "./components/Stories.vue";
import Booking from "./components/Booking.vue";
import Footer from "./components/Footer.vue";
import NavigationBar from "./components/NavigationBar.vue";
import Popup from "./components/Popup.vue";

export default {
  components: {
    "app-header": Header,
    "app-about": About,
    "app-features": Features,
    "app-tours": Tours,
    "app-stories": Stories,
    "app-booking": Booking,
    "app-footer": Footer,
    "app-navigationBar": NavigationBar,
    "app-popup": Popup,
  },
};
</script>
