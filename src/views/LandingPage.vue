<template>
    <div id="landing-page">
        <!-- <h1>Landing Page by Yahya Tampan</h1> -->
        <Header />
        <Banner />
        <Carousel />
        <div class="judul-menu">
            <div class="container">
                <div class="row">
                        <div class="col-lg-6 col-sm-6 col-6">
                            <h1><b>Menu</b> Kami</h1>
                    </div>
                        <div class="col-lg-6 col-sm-6 col-6 text-right">
                            <h1><i class="fas fa-eye"></i> Lihat Semua</h1>
                    </div>
                </div>
            </div>
        </div>
        <Product />
        <Footer />
    </div>
</template>

<script>
import Header from '@/components/Header.vue'
import Banner from '@/components/Banner.vue'
import Carousel from '@/components/Carousel.vue'
import Product from '@/components/Product.vue'
import Footer from '@/components/Footer.vue'

export default {
    name: 'LandingPage',
    components: {
        Header,
        Banner,
        Carousel,
        Product,
        Footer
    }
}
</script>

<style>

</style>
