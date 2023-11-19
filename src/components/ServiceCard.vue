<template>
  <div class="card m-2 p-2">
    <img src="../assets/ezzsteel.svg" class="card-img-top" alt="ezzsteel" />
    <div class="card-body">
      <p class="d-flex justify-content-between">
        <span class="card-title">Card title</span>
        <span class="price">$132</span>
      </p>
      <p class="card-text">
        Some quick example text to build on the card title and make up the bulk of the card's
        content.
      </p>
      <a href="/services" class="btn more text-light">More</a>
    </div>
  </div>
</template>
<style scoped>
.more {
  background-color: #096285;
}

.card {
  width: 300px;
  height: 100%;
  padding: 10px;
  box-sizing: border-box;
}

@media (max-width: 768px) {
  .card {
    width: 250px;
  }
}
</style>
