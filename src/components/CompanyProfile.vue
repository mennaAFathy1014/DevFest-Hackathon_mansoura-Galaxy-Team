<template>
  <div class="container comp-prof p-4 my-5">
    <div class="comp-prof-header d-flex justify-content-between align-items-center">
      <div class="avatar d-flex">
        <img src="../assets/user.svg" alt="avatar" />
        <div class="avatar-info px-3">
          <h3>Zara Company</h3>
          <p>Cairo, Egypt</p>
        </div>
      </div>
      <div class="comp-prof-header-btn">
        <button class="btn main-backclr text-light">Create Service</button>
      </div>
    </div>
    <div class="comp-prof-body">
      <h2>Clothes Company</h2>
      <h3>Summary:</h3>
      <div class="summary">
        Zara is one of the biggest international fashion companies, and it belongs to Inditex, one
        of the world’s largest distribution groups.
        <br />
        <br />
        Zara has an ongoing commitment to its customers around the world in providing an excellent
        customer experience to all. As part of these efforts, we are committed to providing a
        website that is accessible to the widest possible audience, regardless of technology or
        ability. Zara is committed to aligning its website and its operations in substantial
        conformance with generally-recognized and accepted guidelines and/or standards for website
        accessibility (as these may change from time to time). To assist in these efforts, Zara has
        partnered with experienced internationally reputable consultants and is working to increase
        the accessibility and usability of our website.
        <br />
        <br />
        <h3>Our Services:</h3>
        <ol>
          <li>Fast Fashion</li>
          <li>Clothing and Accessories</li>
          <li>In Store Experience</li>
        </ol>
      </div>
    </div>
  </div>
</template>
<style scoped>
.comp-prof {
  border-radius: 10px;
  box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.1);
}
.comp-prof-header {
  border-bottom: 2px solid #ccc;
}
.comp-prof-header .avatar {
  display: flex;
  align-items: center;
  padding-bottom: 10px;
}
.comp-prof-header .avatar img {
  width: 100px;
  height: 100px;
}
.comp-prof-header .avatar-info h3 {
  font-size: 1.5rem;
  font-weight: 600;
}
.comp-prof-header .avatar-info p {
  font-size: 1rem;
  font-weight: 400;
}
.comp-prof-header-btns button {
  border-radius: 5px;
  padding: 5px 10px;
  font-size: 1rem;
  font-weight: 600;
}

.comp-prof-body {
  padding: 20px;
}

.comp-prof-header-btn button:hover {
  background-color: #04364a;
}
</style>
