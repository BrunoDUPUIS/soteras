<script setup>
import Hero from '../components/Hero.vue'
import ServiceCard from '../components/ServiceCard.vue'
import CTA from '../components/CTA.vue'
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
          image="src/assets/imgs/ecs.jpeg"
        />

        <ServiceCard
          title="Chauffage"
          description="Installation de chauffage moderne"
          image="src/assets/imgs/thermo.jpeg"
        />
        <ServiceCard
          title="Dépannage"
          description="Intervention rapide 7j/7"
          image="src/assets/imgs/depannage.jpeg"
        />
      </div>
    </section>

    <CTA />
  </div>
</template>
