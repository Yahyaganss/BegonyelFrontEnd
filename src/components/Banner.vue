<template>
    <div id="Banner">
      <div class="container">
        <div class="row">
            <div class="col-lg-6">
              <div class="banner-text">
                <h6>FoodMarket</h6>
                <h1 class="my-3">Waktunya <br/>pilih menu<span> favorite </span>kamu</h1>
                <h6>mulai dari Rp 20.000</h6>
                <div class="row">
                        <router-link to="/list-product"><button type="button" class="btn btn-light">Lihat Menu</button></router-link>
                        <router-link to="/product-detail"><button type="button" class="btn btn-success">Pesan <i class="fas fa-arrow-right"></i></button></router-link>
                </div>
              </div>  
            </div>
            <div class="col-lg-6">
              <div class="banner-image">
                <img src="../assets/banner.png" alt="banner">
              </div>  
            </div>  
        </div>
      </div>  
    </div>
</template>

<script>
export default {
    name: 'Banner'   
}
</script>

<style>

</style>