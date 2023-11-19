<template>
  <div class="container">
    <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="../assets/LinkoLogo.svg" alt="" />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <RouterLink to="/" aria-current="page" href="#" exact>Home</RouterLink>
            </li>
            <li class="nav-item">
              <router-link to="/find-service" href="#">Find Service</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/requests" href="#">Requests</router-link>
            </li>
            <!-- <li class="nav-item">
              <router-link to="/find-service" href="#"></router-link>
            </li> -->
          </ul>
          <form class="d-flex search-form" role="search">
            <!-- input field with icon search -->
            <button type="button" class="btn btn-outline-primary">
              <i class="bi bi-search"></i>
            </button>
            <div class="input-group">
              <input
                type="search"
                class="form-control rounded"
                placeholder="Search"
                aria-label="Search"
                aria-describedby="search-addon"
              />
            </div>
          </form>
          <!-- icon bell -->
          <div class="icon">
            <i class="bi bi-bell"></i>
          </div>
          <!-- user profile -->
          <div class="user p-2">
            <img src="../assets/user.svg" alt="" />
          </div>

          <!-- login btn signup logout -->
          <div class="login-btns">
            <!-- <button class="btn login-btn main-backclr text-light">
              <router-link to="/login" href="#">Login</router-link>
            </button>

            <button class="btn signup-btn">
              <router-link to="/signup" href="#">Sign Up</router-link>
            </button> -->

            <button class="btn logout-btn">
              <router-link to="/logout" href="#">Logout</router-link>
            </button>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
<script setup></script>
<style scoped>
ul li a {
  color: #000 !important;
  text-decoration: none;
  padding: 5px;
}
ul li a.router-link-active.router-link-exact-active {
  color: #096285 !important;
  text-decoration: none;
}
.search-form {
  width: 100%;
  max-width: 400px;
  background-color: #fff;
  border-radius: 5px;
  border: 1px solid #ccc;
  padding: 5px;
  display: flex;
  align-items: center;
  margin: 0 10px;
}
.search-form .input-group {
  width: 100%;
}
.search-form .input-group input {
  border: none;
  box-shadow: none;
  padding: 0;
  margin: 0;
}
.search-form .input-group input:focus {
  outline: none;
  box-shadow: none;
}
.search-form .input-group input::placeholder {
  color: #ccc;
}
.search-form button {
  border: none;
  box-shadow: none;
  padding: 10px;
  margin: 0;
  background-color: transparent;
  color: #ccc;
}
.search-form > button:hover {
  background-color: transparent;
  color: #000;
}
.login-btns .btn {
  margin-inline: 5px;
}
.login-btns .btn a {
  text-decoration: none;
}
.login-btns .login-btn:hover {
  background-color: #04364a;
}
.login-btns .login-btn a {
  color: #fff;
}
.login-btns .signup-btn:hover {
  border: #04364a 1px solid;
}
.login-btns .signup-btn a,
.login-btns .logout-btn a {
  color: #000;
}

@media (max-width: 768px) {
  .search-form,
  .icon,
  .user {
    display: none !important;
  }
}
</style>
