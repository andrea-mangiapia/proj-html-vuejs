<template>
    <section class="jumbotron">
        <div class="container">
            <div class="content-jumbo am-flex">
                <div class="img-jumbo">
                    <div class="hero-img-1">
                        <img src="../assets/img/artist-hero-image-01.jpg" alt="Artist Hero">
                    </div>
                    <div class="hero-img-2">
                        <img src="../assets/img/artist-hero-image-02.jpg" alt="Artist Hero">
                    </div>
                </div>
                <div class="cta-jumbo">
                    <div class="font-style-italic">
                        Hello, Im Martin
                    </div>
                    <h2>
                        Artist Coaching And Mentoring Might Be for You.
                    </h2>
                    <button class="btn btn-primary">Get started today</button>

                </div>
                <div class="img-jumbo">
                    <div class="hero-img-3">
                        <img src="../assets/img/artist-hero-image-04.jpg" alt="Artist Hero">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "MyJumbotron",
}
</script>

<style lang="scss" scoped>
@import '../assets/style/variables.scss';
.jumbotron {
    background-color: $brand_primary_color;
    padding: 30px 0;

    .content-jumbo {
        align-items: center;
    }

    .img-jumbo {
        width: 30%;
    }
    .cta-jumbo {
        width: 40%;
        text-align: center;

        .font-style-italic {
            font-size: 60px;
        }

        h2 {
        font-size: 40px;
        }
    }

    .img-jumbo {
        position: relative;
        height: 550px;
    }
    .hero-img-1 {
        width: 41%;
        position: absolute;
        left: 0;
        bottom: 0;
        z-index: 2;
    }
    .hero-img-2 {
        width: 61%;
        position: absolute;
        right: 0px;
        top: 0;
    }
    .hero-img-3 {
        width: 80%;
        position: absolute;
        right: 0;
        bottom: 0;
    }



}
</style>