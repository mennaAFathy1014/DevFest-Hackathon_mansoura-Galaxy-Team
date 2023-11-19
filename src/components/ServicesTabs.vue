<template>
  <div id="app" class="container">
    <ul class="filters">
      <li>
        <button
          class="btn btn-outline-primary"
          @click="isActive = 'allCompanies'"
          :class="[isActive === 'allCompanies' ? ActiveClass : '']"
        >
          All Companies
        </button>
      </li>
      <li>
        <button
          class="btn btn-outline-primary"
          @click="isActive = 'manufacturing'"
          :class="{ active: isActive === 'manufacturing' }"
        >
          Manufacturing
        </button>
      </li>
      <li>
        <button
          class="btn btn-outline-primary"
          @click="isActive = 'ecommerce'"
          :class="{ active: isActive === 'ecommerce' }"
        >
          E-commerce
        </button>
      </li>
      <li>
        <button
          class="btn btn-outline-primary"
          @click="isActive = 'medicalServices'"
          :class="{ active: isActive === 'medicalServices' }"
        >
          Medical Services
        </button>
      </li>
    </ul>
    <div class="services">
      <ServiceCard />
      <ServiceCard />
      <ServiceCard />
      <ServiceCard />
      <ServiceCard />
      <ServiceCard />
    </div>
  </div>
</template>
<script setup>
import { ref, onMounted } from 'vue'
import ServiceCard from './ServiceCard.vue'

const isActive = ref(false)
const ActiveClass = ref('active')

onMounted(() => {
  isActive.value = 'allCompanies'
})
</script>

<style scoped>
ul {
  display: flex;
  border-bottom: #c9c9c9 1px solid;
}
ul li button.btn {
  margin: 5px;
  border: none;
  box-shadow: none;
  padding: 10px;
  background-color: transparent;
  color: #ccc;
}
ul li button.btn:hover {
  background-color: transparent;
  color: #000;
}
ul li button.btn.active {
  background-color: transparent;
  color: #000;
}

.services {
  display: flex;
  flex-wrap: wrap;
  margin-top: 20px;
}
</style>
