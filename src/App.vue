<script setup>
import Navbar from '../src/components/Navbar.vue';
import Hero from '../src/components/Hero.vue';
import Homecards from '../src/components/HomeCards.vue';
import JobListings from '../src/components/JobListings.vue';
</script>

<template>
  <div>
 <Navbar />
 <Hero title="Jobs For Frontend Dev" subtitle="Find the Vue job that fits your skills and needs"/>
 <Homecards/>
 <JobListings :limit="3" :showButton="true"/>
</div>
</template>