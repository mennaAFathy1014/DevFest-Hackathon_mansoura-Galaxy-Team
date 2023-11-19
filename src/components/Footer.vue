<template>
  <footer class="main-backclr">
    <div class="container">
      <!-- logo -->
      <div class="logo">
        <img src="../assets/footerlogo.svg" alt="logo" />
      </div>
      <!-- links -->
      <div class="links">
        <ul>
          <li>
            <a href="#">Services</a>
          </li>
          <li>
            <a href="#">About Us</a>
          </li>
          <li>
            <a href="#">Courses</a>
          </li>
          <li>
            <a href="#">FAQ</a>
          </li>
        </ul>
      </div>
      <!-- social media -->
      <div class="social-media">
        <ul>
          <li>
            <h3>Contact Us</h3>
          </li>
          <li>
            <a href="#">
              <i class="bi bi-telephone-inbound"></i>
              <span class="m-2">010111111111</span>
            </a>
          </li>
          <li>
            <a href="#">
              <i class="bi bi-envelope-fill"></i>
              <span class="m-2">Linko@gmail.com</span>
            </a>
          </li>
          <li>
            <p href="#">
              <i class="bi bi-geo-alt"></i>
              <span class="m-2">Egypt</span>
            </p>
          </li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<script setup></script>

<style>
footer {
  background-color: #f8f9fa;
  padding: 50px 0;
}
footer .container {
  display: grid;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 20px;
}
@media (max-width: 768px) {
  footer .container {
    grid-template-columns: repeat(1, 1fr);
  }
}
footer .container .logo {
  margin-bottom: 20px;
}
footer .container .logo img {
  width: 200px;
}
footer .container .links ul {
  display: flex;
  flex-direction: column;
  margin-bottom: 20px;
}
footer .container .links ul li {
  margin-bottom: 10px;
}
footer .container .links ul li a {
  color: #fff;
  text-decoration: none;
}
footer .container .links ul li a:hover {
  color: #fff;
  text-decoration: none;
}
footer .container .social-media ul {
  flex-direction: column;
  margin-bottom: 20px;
}
footer .container .social-media ul li {
  margin-right: 10px;
}
footer .container .social-media ul li p {
  margin-bottom: 10px;
  color: #fff;
}
footer .container .social-media ul li a,
footer .container .social-media ul li h3 {
  color: #fff;
  text-decoration: none;
}
footer .container .social-media ul li a:hover {
  color: #fff;
  text-decoration: none;
}
@media (max-width: 768px) {
  footer .container .logo,
  footer .container .links ul,
  footer .container .social-media ul {
    margin-bottom: 20px;
    display: flex;
  }
}
footer ul {
  list-style: none;
}
</style>
