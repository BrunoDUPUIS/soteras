<script setup>
import Navbar from './components/Navbar.vue'
import Footer from './components/Footer.vue'
import GoogleMap from './components/GoogleMap.vue'
import ContactBanner from './components/ContactBanner.vue'
</script>

<template>
  <div>
    <Navbar />

    <router-view />

    <ContactBanner />

    <GoogleMap />

    <Footer />
  </div>
</template>
