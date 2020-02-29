<template>
    <section id="slider" class="slider-element slider-parallax full-screen with-header clearfix">
        <div class="slider-parallax-inner">
            <div class="swiper-container swiper-parent">
                <div class="">
                    <div class="swiper-slide dark" id="slide1">
                        <div class="container clearfix">
                            <div class="slider-caption slider-caption-center">
                                <h2 data-animate="fadeInUp">{{ title }}</h2>
                                <p class="d-none d-sm-block" data-animate="fadeInUp" data-delay="200">{{ subtitle }}</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'CanvasSlider',
        props: {
            title: String,
            subtitle: String
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    h2 {
        padding: 170px 0 100px 0;
    }
    #slide1 {
        background-image: url('/images/slider/swiper/1.jpg');
        height: 100vh;
        width: 100%;
        background-position: 50% 20% !important;
    }
</style>
