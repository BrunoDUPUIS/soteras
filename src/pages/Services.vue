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
        image="./images/sbd.webp"
      />

      <ServiceCard
        title="Recherche de fuite"
        description="Détection et réparation rapide"
        image="./images/recherche-de-fuite.webp"
      />

      <ServiceCard
        title="Pompe à chaleur"
        description="Solutions économiques et performantes"
        image="./images/pac.webp"
      />
    </div>
  </section>
</template>
