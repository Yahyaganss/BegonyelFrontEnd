<template>
  <div id="ListProduct">
    <Header />
    <div class="container">
      <nav aria-label="breadcrumb">
        <ol class="breadcrumb">
          <li class="breadcrumb-item">
            <a href="#/"><i class="fas fa-home"></i> Home</a>
          </li>
          <li class="breadcrumb-item">
            <a href="#"><b>ListProduct</b></a>
          </li>
        </ol>
      </nav>
      <div class="search-box">
        <input type="text" class="input" placeholder="Mau makan apa hari ini..."><button class="btn-searchBox"><i class="fas fa-search"></i></button>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-lg-3">
          <div class="card">
            <img src="../assets/product-cake.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Es Buah Everest</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <a href="#" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></a>
            </div>
          </div>
        </div>
        <div class="col-lg-3">
            <div class="card">
            <img src="../assets/product-lontongOporAyam.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Es Buah Everest</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <a href="#" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></a>
            </div>
          </div>
        </div>
        <div class="col-lg-3">
            <div class="card">
            <img src="../assets/product-mieGoreng.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Es Buah Everest</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <a href="#" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></a>
            </div>
          </div>
        </div>
        <div class="col-lg-3">
            <div class="card">
            <img src="../assets/product-ayamGeprek.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Es Buah Everest</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <a href="#" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-lg-3">
          <div class="card">
            <img src="../assets/product-nasiRames.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Es Buah Everest</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <a href="#" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></a>
            </div>
          </div>
        </div>
        <div class="col-lg-3">
            <div class="card">
            <img src="../assets/product-nasiGorengTelor.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Es Buah Everest</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <a href="#" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></a>
            </div>
          </div>
        </div>
        <div class="col-lg-3">
            <div class="card">
            <img src="../assets/product-sate.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Es Buah Everest</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <a href="#" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></a>
            </div>
          </div>
        </div>
        <div class="col-lg-3">
            <div class="card">
            <img src="../assets/product-bakso.png" class="card-img-top" alt="..." />
            <div class="card-body">
              <h5 class="card-title">Es Buah Everest</h5>
              <p class="card-text">
                  Harga : Rp 15.000
              </p>
              <a href="#" class="btn btn-primary">Pesan Sekarang <i class="fas fa-arrow-right"></i></a>
            </div>
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue"
import Footer from "@/components/Footer.vue"

export default {
  name: "ListProduct",
  components: {
    Header,
    Footer
  },
};
</script>

<style>
</style>