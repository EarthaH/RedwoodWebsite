<template>
  <div class="home">
    <NavbarComponent/>
    <section class="hero is-link is-fullheight-with-navbar">
      <div class="hero-body">
        <div class="container has-text-centered" id="banner-container">
          <h1 class="title" id="banner-title">REDWOOD</h1>
          <h2 class="subtitle" id="banner-subtitle">Hogsback Accommodation</h2>
        </div>
      </div>
    </section>
    <AboutComponent/>
    <hr/>
    <GalleryComponent/>
    <hr/>
    <LocationComponent/>
    <hr/>
    <PriceComponent/>
    <hr/>
    <ContactComponent/>
  </div>
</template>

<script>
// @ is an alias to /src
// import { AboutView } from "./AboutView.vue";
import AboutComponent from '@/components/AboutComponent'
import GalleryComponent from '../components/GalleryComponent.vue'
import PriceComponent from '../components/PriceComponent.vue'
import ContactComponent from '../components/ContactComponent.vue'
import NavbarComponent from '../components/NavbarComponent.vue'
import LocationComponent from '../components/LocationComponent.vue'

export default {
  name: 'HomeView',
  components: {
    AboutComponent,
    GalleryComponent,
    PriceComponent,
    ContactComponent,
    NavbarComponent,
    LocationComponent
},
};
</script>

<style lang="scss" scoped src="../styles/styles.scss"></style>
