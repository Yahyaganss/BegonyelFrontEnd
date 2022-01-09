<template>
  <div id="Header">
      <nav class="navbar navbar-expand-lg navbar-light">
        <div class="container">
            <router-link to="/">
              <a class="navbar-brand" href="#">
                <img src="../assets/logo-begonyel.png" alt="">
              </a>
            </router-link>
          <button
            class="navbar-toggler"
            type="button"
            data-toggle="collapse"
            data-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item active">
                <router-link to="/" class="nav-link">Home</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/list-product" class="nav-link">Menu Makanan</router-link>
              </li>
              <li class="nav-item">
                <router-link to="/keranjang" class="nav-link">Keranjang <i class="fas fa-shopping-bag"></i></router-link>
              </li>
            </ul>
          </div>
        </div>  
      </nav>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
    #Header {
      list-style-type: none;
    }
</style>