<script setup>
import HeroItem from '@/components/HeroItem.vue'
import HomeCards from '@/components/HomeCards.vue'
import JobListings from '@/components/JobListings.vue'
</script>

<template>
  <HeroItem />
  <HomeCards />
  <JobListings :limit="3" :showButton="true" />
</template>
