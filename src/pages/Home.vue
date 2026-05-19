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
          image="/images/ecs.webp"
        />

        <ServiceCard
          title="Chauffage"
          description="Installation de chauffage moderne"
          image="/images/thermo.webp"
        />
        <ServiceCard
          title="Dépannage"
          description="Intervention rapide 7j/7"
          image="images/depannage.webp"
        />
      </div>
    </section>

    <CTA />
  </div>
</template>
