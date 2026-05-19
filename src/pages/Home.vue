<script setup>
import Hero from '../components/Hero.vue'
import ServiceCard from '../components/ServiceCard.vue'
import CTA from '../components/CTA.vue'

import plomberieImg from '../assets/imags/ecs.webp'
import chauffageImg from '../assets/imags/thermo.webp'
import depannageImg from '../assets/imags/depannage.webp'
</script>

<template>
  <div>
    <Hero />

    <section class="services-preview container">
      <h2>Nos services</h2>

      <div class="services-grid">
        <ServiceCard
          title="Plomberie"
          description="Installation et dépannage plomberie"
          :image="plomberieImg"
        />

        <ServiceCard
          title="Chauffage"
          description="Installation de chauffage moderne"
          :image="chauffageImg"
        />

        <ServiceCard
          title="Dépannage"
          description="Intervention rapide 7j/7"
          :image="depannageImg"
        />
      </div>
    </section>

    <CTA />
  </div>
</template>
