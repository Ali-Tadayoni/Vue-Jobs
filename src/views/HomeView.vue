<script setup>
import Hero from "../components/Hero.vue";
import HomeCards from "../components/HomeCards.vue";
import JobListings from "../components/JobListings.vue";
</script>

<template>
  <Hero title="Lets do it" subtitle="Test for subtitle" />
  <HomeCards />
  <JobListings :limit="3" :showButton="true" />
</template>
