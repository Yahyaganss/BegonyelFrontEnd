<template>
  <div id="Keranjang">
    <Header />
    <div class="container">
      <nav aria-label="breadcrumb">
        <ol class="breadcrumb">
          <li class="breadcrumb-item">
            <a href="#/"><i class="fas fa-home"></i> Home</a>
          </li>
          <li class="breadcrumb-item">
            <a href="#"><b>Keranjang</b></a>
          </li>
        </ol>
      </nav>
      <table class="table table-borderless">
      <thead>
        <tr>
          <th scope="col">Produk</th>
          <th scope="col">Nama</th>
          <th scope="col">Keterangan</th>
          <th scope="col-2">Jumlah</th>
          <th scope="col">Harga</th>
          <th scope="col">Aksi</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row"><img src="../assets/product-ayamGeprek2.png" alt=""></th>
          <td>Nasi Geprek Klenger</td>
          <td >Pedes level 3 yaa, mantapp loor</td>
          <td>1</td>
          <td>Rp 20.000</td>
          <td><button type="button" class="btn btn-light"><i class="fas fa-trash"></i></button></td>
        </tr>
      </tbody>
      </table>
      <hr color="#F57C00">
      <h4><b>Total Harga : Rp 20.000</b></h4>
      <div class="row justify-content-end">
        <div class="col-lg-5">
          <div class="form-group">  
            <label>Nama Pemesan</label>
            <input class="form-control" rows="1"/>
          </div>
          <div class="form-group">  
            <label>Nomor Meja</label>
            <input class="form-control" rows="1"/>
          </div>
        </div>
      </div>
      <div class="row justify-content-end mt-4">
        <router-link to="/success"><button type="button" class="btn btn-success">Pesan Sekarang <i class="fas fa-arrow-right"></i></button></router-link>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
import Header from "@/components/Header.vue"
import Footer from "@/components/Footer.vue"

export default {
  name: "Keranjang",
  components: {
      Header,
      Footer
  },
};
</script>

<style>
</style>