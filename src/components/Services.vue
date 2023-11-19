<template>
  <div class="container">
    <div class="services">
      <div class="service-box">
        <h2 class="p-2">Service</h2>
      </div>
      <div class="services-body">
        <div class="service-box">
          <ServiceGigCard />
        </div>
        <div class="service-box">
          <ServiceGigCard />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import ServiceGigCard from '../components/ServiceGigCard.vue'
</script>

<style scoped>
.services {
  margin: 40px 0;
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.service-box {
  border-bottom: 1px solid #ccc;
  margin-block: 20px;
}
.service-box:last-child {
  border-bottom: none;
}
</style>
