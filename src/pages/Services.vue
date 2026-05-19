<script setup>
import ServiceCard from '../components/ServiceCard.vue'
</script>

<template>
  <section class="page container">
    <h1>Nos services</h1>

    <div class="services-grid">
      <ServiceCard
        title="Salle de bain"
        description="Création et rénovation complète"
        image="public/images/sbd.jpeg"
      />

      <ServiceCard
        title="Recherche de fuite"
        description="Détection et réparation rapide"
        image="public/images/recherche-de-fuite.jpeg"
      />

      <ServiceCard
        title="Pompe à chaleur"
        description="Solutions économiques et performantes"
        image="public/images/pac.jpeg"
      />
    </div>
  </section>
</template>
