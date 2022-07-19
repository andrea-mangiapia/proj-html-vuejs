<template>
    <div>
        <!-- Services List -->
        <section>
            <div class="container-short">
                <div class="font-style-italic">
                    Artist coaching
                </div>
                <h2>
                    I understand what it takes to create. I can help you with
                </h2>
                <div class="services-list am-flex">
                    <div class="card">
                        <img src="../assets/img/artist-box-image-01.png" alt="Artist Box">
                        <h3>
                            Online Courses
                        </h3>
                        <p>
                            Online art coaching now offers you a very powerful way to redesign your artist mind.
                        </p>
                    </div>
                    <div class="card">
                        <img class="img-tall" src="../assets/img/artist-box-image-02.png" alt="Artist Box">
                        <h3>
                            One to One
                        </h3>
                        <p>
                            Online art coaching now offers you a very powerful way to redesign your artist mind.
                        </p>
                    </div>
                    <div class="card">
                        <img src="../assets/img/artist-box-image-03.png" alt="Artist Box">
                        <h3>
                            Online Courses
                        </h3>
                        <p>
                            Online art coaching now offers you a very powerful way to redesign your artist mind.
                        </p>
                    </div>
                    <div class="card">
                        <img class="img-tall" src="../assets/img/artist-box-image-04.png" alt="Artist Box">
                        <h3>
                            Online Courses
                        </h3>
                        <p>
                            Online art coaching now offers you a very powerful way to redesign your artist mind.
                        </p>
                    </div>

                    
                </div>
            </div>
        </section>
        <!-- Aphorism and Motivate-->
        <section>
            <div class="container-short">
                <div class="quote-motivate am-flex">
                    <div class="quote am-col-2">
                        <img class="img-quote" src="../assets/img/artist-quote-icon.png" alt="quote">
                        <div class="text-quote">
                            I coach and mentor visual artists, like you, to Create Like You Mean It
                        </div>
                        <div class="font-style-italic">
                            Martin Garrix                            
                        </div>
                    </div>
                    <div class="am-col-2">
                        <div>
                            <p>
                                As a coach and mentor, my ultimate goal is to motivate visual artists toward inspired action. I help you get you back on track to being the productive, creative, meaningful and authentic artist you truly want to be.I support artists in crafting and living a creative life as well as feeling good about themselves and their art.
                            </p>
                            <p>
                                As an artist and an educator for nearly 30 years, I understand what it takes to create.
                            </p>
                        </div>
                        <button class="btn btn-secondary">
                            Get started today
                        </button>
                    </div>
                </div>
            </div>
        </section>
        <section>
            <div class="container-short">
                Video
            </div>
        </section>
    </div>
</template>

<script>
export default {
    name: "SectionServices",

}
</script>

<style lang="scss" scoped>
.services-list {
    padding: 30px 0;

    .card {
        padding: 15px;

        h3 {
            padding-top: 10px;
        }

        img {
        width: auto;
        height: 115px;
        }
        .img-tall {
            margin-top: 50px;
            height: 85px;
        }
    }
}

.quote-motivate {
    align-items: flex-end;
    

    .am-col-2 {
        width: 50%;
    }
    .quote {
        text-align: center;
        padding-right: 200px;

        .img-quote {
            width: 40px;
            margin: 0 auto;
        }
        .text-quote {
            font-size: 45px;
            font-weight: 700;
            padding-top: 20px;
            line-height: 1.4;
        }
    }

    p {
        margin-bottom: 1.7em;
    }

}

</style>