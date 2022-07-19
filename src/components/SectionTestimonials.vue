<template>
    <section>
        <div>
            <div class="font-style-italic">
                Testimonials
            </div>
            <h2>
                Why do people love me?
            </h2>
            <div class="testimonials-list am-flex">
                <div class="testimonial">
                    <div class="t-card t-left">
                        <div class="t-content">
                            <h4>
                                It's a choice of quality for people with special needs
                            </h4>
                            <div class="t-text">
                                I'm a very strict person so I require everything to be organized and neat. Then, I'll be able to make things right and shine. MaxCoach guys just got me.
                            </div>
                            <div class="t-autor am-flex">
                                <div class="t-img">
                                    <img src="../assets/img/artist-testimonial-avatar-02.jpg" alt="Florence Themes">
                                </div>
                                <div>
                                    <h6 class="t-name">
                                        Florence Themes
                                    </h6>
                                    <div class="t-position">
                                        / Multimedia Admin
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="testimonial">
                    <div class="t-card t-center">
                        <div class="t-content">
                            <h4>
                                High level of efficiency and scientific teaching methods
                            </h4>
                            <div class="t-text">
                                I am free to learn at my own pace, follow my own schedule and choose the subject I want to learn from the syllabus. Great study portal for people like me.
                            </div>
                            <div class="t-autor am-flex">
                                <div class="t-img">
                                    <img src="../assets/img/artist-testimonial-avatar-04.jpg" alt="Mina Hollace">
                                </div>
                                <div>
                                    <h6 class="t-name">
                                        Mina Hollace
                                    </h6>
                                    <div class="t-position">
                                        / Freelancer
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="testimonial">
                    <div class="t-card t-right">
                        <div class="t-content">
                            <h4>
                                Professional team of specialists and passionate mentors at reach 
                            </h4>
                            <div class="t-text">
                                I need to get a certification for English proficiency and MaxCoach is my best choice. Their tutors are smart and professional when dealing with students.
                            </div>
                            <div class="t-autor am-flex">
                                <div class="t-img">
                                    <img src="../assets/img/artist-testimonial-avatar-01.jpg" alt="Madley Pondor">
                                </div>
                                <div>
                                    <h6 class="t-name">
                                        Madley Pondor
                                    </h6>
                                    <div class="t-position">
                                        / IT Specialist
                                    </div>
                                </div>
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
    name: "SectionTestimonials",

}
</script>

<style lang="scss" scoped>
@import '../assets/style/variables.scss';

section {
    background-color: $brand_primary_color;
    padding: 50px;

    .testimonial {
        width: calc((100% / 3));

        .t-card {
            background-color: white;
            border-radius: 4px;
            margin: 25px;
            padding: 50px;

            h4, .t-text {
                margin-bottom: 20px;
            }
            .t-autor {
                align-items: center;
            }

            .t-img img {
                width: 70px;
                border-radius: 50%;
                margin-right: 20px;
            }
            h6, .t-position {
                font-size: 15px;
            }
            .t-position {
                color: darkgray;
            }
        }

        .t-left, .t-right {
            opacity: 0.5;
        }
    }
}
</style>