<template>
  <div class="container p-4">
    <form class="request-form">
      <div class="mb-3">
        <h2>Service Request</h2>
      </div>
      <div class="mb-3">
        <label for="type-of-request" class="form-label">Type of Request</label>
        <input type="text" class="form-control" id="type-of-request" />
      </div>
      <div class="mb-3">
        <label for="add-description" class="form-label">Add Description</label>
        <textarea
          class="d-block"
          name="add-description"
          id="add-description"
          cols="30"
          rows="10"
        ></textarea>
      </div>
      <div class="mb-3">
        <label for="service-standards" class="form-label">Service Standards</label>
        <input type="text" class="form-control" id="service-standards" />
      </div>
      <div class="mb-3">
        <label for="type-of-request" class="form-label">Quantity</label>
        <input type="text" class="form-control" id="type-of-request" />
      </div>
      <div class="mb-3">
        <butoon class="publish btn main-backclr text-light">publish </butoon>
      </div>
    </form>
  </div>
</template>
<style scoped>
textarea {
  width: 100%;
  height: 100px;
  border-radius: 5px;
  border: 1px solid #ccc;
  padding: 10px;
  resize: none;
  font-size: 16px;
  font-family: sans-serif;
  box-sizing: border-box;
  margin-top: 10px;
  margin-bottom: 10px;
}
textarea:focus,
input:focus {
  outline: none;
  box-shadow: none;
  border: #ccc 1px solid;
}
</style>
