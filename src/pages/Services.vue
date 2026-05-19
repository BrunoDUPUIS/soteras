<script setup>
import ServiceCard from '../components/ServiceCard.vue'
import SalleDeBainImg from '../assets/imags/sbd.webp'
import RechercheDeFuiteImg from '../assets/imags/recherche-de-fuite.webp'
import PompesAChaleurImg from '../assets/imags/pac.webp'
</script>

<template>
  <section class="page container">
    <h1>Nos services</h1>

    <div class="services-grid">
      <ServiceCard
        title="Salle de bain"
        description="Création et rénovation complète"
        :image="SalleDeBainImg"
      />

      <ServiceCard
        title="Recherche de fuite"
        description="Détection et réparation rapide"
        :image="RechercheDeFuiteImg"
      />

      <ServiceCard
        title="Pompe à chaleur"
        description="Solutions économiques et performantes"
        :image="PompesAChaleurImg"
      />
    </div>
  </section>
</template>
