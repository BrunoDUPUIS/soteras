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
        image="src/assets/imgs/sbd.jpeg"
      />

      <ServiceCard
        title="Recherche de fuite"
        description="Détection et réparation rapide"
        image="src/assets/imgs/recherche-de-fuite.jpeg"
      />

      <ServiceCard
        title="Pompe à chaleur"
        description="Solutions économiques et performantes"
        image="src/assets/imgs/pac.jpeg"
      />
    </div>
  </section>
</template>
