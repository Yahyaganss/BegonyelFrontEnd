<template>
  <div id="Product">
    <div class="container">
      <div class="row">
        <div class="col-lg-3">
          <div class="card">
            <img src="../assets/product-nasiRames.png" class="card-img-top" alt="..." />
              <h5 class="card-title">Nasi Rames</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <router-link to="/product-detail" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></router-link>
          </div>
        </div>
        <div class="col-lg-3">
          <div class="card">
            <img src="../assets/product-sate.png" class="card-img-top" alt="..." />
              <h5 class="card-title">Sate Panggang</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <router-link to="/product-detail" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></router-link>
          </div>
        </div>
        <div class="col-lg-3">
            <div class="card">
            <img src="../assets/product-sate.png" class="card-img-top" alt="..." />
              <h5 class="card-title">Sate Bakar</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <router-link to="/product-detail" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></router-link>
          </div>
        </div>
        <div class="col-lg-3">
          <div class="card">
            <img src="../assets/product-bakso.png" class="card-img-top" alt="..." />
              <h5 class="card-title">Bakso Sapi</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <router-link to="/product-detail" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></router-link>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Product",
};
</script>

<style>
    router-link {
      text-decoration: none;
    }
</style>