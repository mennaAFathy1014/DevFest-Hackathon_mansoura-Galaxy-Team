<template>
  <div class="service-gig">
    <div class="service-gig-title">
      <h3>Fabrics and threads</h3>
    </div>
    <div class="service-gig-body">
      <p class="gig-description">
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
        been the industry's standard dummy text ever since the 1500s, when an unknown printer took a
        galley of type and scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining essentially unchanged.
      </p>
      <div class="gig-price">
        <span class="price">$132</span>
      </div>

      <div class="gig-footer">
        <div class="location">
          <i class="bi bi-geo-alt-fill"></i>
          <span class="location-text">Cairo, Egypt</span>
        </div>
        <div class="gig-btn">
          <button class="btn main-backclr">Apply Now</button>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.service-gig {
  width: 100%;
  height: 100%;
  padding: 10px;
  box-sizing: border-box;
}
.service-gig-title {
  margin-bottom: 10px;
}
.service-gig-title h3 {
  font-size: 20px;
  font-weight: 600;
}
.gig-description {
  font-size: 16px;
  font-weight: 400;
  line-height: 1.5;
  margin-bottom: 10px;
}
.gig-price {
  margin-bottom: 10px;
}
.gig-price .price {
  font-size: 18px;
  font-weight: 600;
}
.gig-footer {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.gig-footer .location {
  display: flex;
  align-items: center;
}
.gig-footer .location .location-text {
  font-size: 14px;
  font-weight: 400;
  margin-left: 5px;
}
.gig-footer .gig-btn {
  width: 100px;
}
.gig-footer .gig-btn .btn {
  width: 100%;
  padding: 5px;
  font-size: 14px;
  font-weight: 600;
  color: #fff;
}
.gig-footer .gig-btn .btn:hover {
  background-color: #096285;
}
</style>
