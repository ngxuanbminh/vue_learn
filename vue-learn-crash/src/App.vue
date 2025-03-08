<script setup>
import NavBar from '@/components/NavBar.vue'
import HeroItem from './components/HeroItem.vue'
import HomeCards from './components/HomeCards.vue'
import JobListings from './components/JobListings.vue'
</script>

<template>
  <NavBar />
  <HeroItem />
  <HomeCards />
  <JobListings :limit="3" :showButton="true" />
</template>
