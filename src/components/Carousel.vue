<template>
  <div id="Carousel">
    <div class="container">
      <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators justify-content-start">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active p-2">
            <img src="../assets/carousel.png" class="d-block w-100" alt="carousel" />
          </div>
          <div class="carousel-item p-2">
            <img src="../assets/carousel.png" class="d-block w-100" alt="carousel" />
          </div>
          <div class="carousel-item p-2">
            <img src="../assets/carousel.png" class="d-block w-100" alt="carousel" />
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
  </div>
</template>

<script>
export default {
  name: "Carousel",
};
</script>

<style>
</style>