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
          image="public/images/ecs.jpeg"
        />

        <ServiceCard
          title="Chauffage"
          description="Installation de chauffage moderne"
          image="public/images/thermo.jpeg"
        />
        <ServiceCard
          title="Dépannage"
          description="Intervention rapide 7j/7"
          image="public/images/depannage.jpeg"
        />
      </div>
    </section>

    <CTA />
  </div>
</template>
