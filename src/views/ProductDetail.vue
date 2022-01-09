<template>
    <div id="ProductDetail">
    <Header />
    <div class="container">
      <nav aria-label="breadcrumb">
        <ol class="breadcrumb">
          <li class="breadcrumb-item">
            <a href="#/"><i class="fas fa-home"></i> Home</a>
          </li>
          <li class="breadcrumb-item">
            <a href="#"><b>ProductDetails</b></a>
          </li>
        </ol>
      </nav>
      <div class="row">
        <div class="col-lg-5">
            <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators justify-content-center">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active p-2">
            <img src="../assets/product-ayamGeprek2.png" class="d-block w-100" alt="carousel" />
          </div>
          <div class="carousel-item p-2">
            <img src="../assets/product-ayamGeprek2.png" class="d-block w-100" alt="carousel" />
          </div>
          <div class="carousel-item p-2">
            <img src="../assets/product-ayamGeprek2.png" class="d-block w-100" alt="carousel" />
          </div>
        </div>
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <i class="fas fa-arrow-circle-left"></i>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <i class="fas fa-arrow-circle-right"></i>
        </a>
      </div>
        </div>
        <div class="col-lg-6 ml-5">
          <h1>Nasi Geprek Klenger</h1>
          <h4>Harga : <b>Rp. 20.000</b></h4>
          <hr size="2px">
          <div class="form-group">
            <label for="">Pesanan</label>
            <input type="number" value="1" min="1" class="form-control" id="jumlah-pesanan" name="jumlahPesanan" aria-describedby="helpId" placeholder="">
          </div>
          <div class="form-group">  
            <label for="">Keterangan</label>
            <textarea class="form-control" rows="5" placeholder="Contoh : Pedas, Banyakin Kecap Asin -_-"></textarea>
          </div>
          <router-link to="/keranjang"><button type="button" class="btn btn-success">Masukkan Keranjang <i class="fas fa-arrow-right"></i></button></router-link>
        </div>
      </div>
      <div class="judul-menu">
            <div class="container">
                <div class="row">
                        <div class="col-lg-6 text-left">
                            <h1><b>Menu</b> Kami</h1>
                    </div>
                        <div class="col-lg-6 text-right">
                            <h1><i class="fas fa-eye"></i> Lihat Semua</h1>
                    </div>
                </div>
            </div>
      </div>
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
  name: "ProductDetail",
  components: {
      Header,
      Footer
  },
};
</script>

<style>
</style>