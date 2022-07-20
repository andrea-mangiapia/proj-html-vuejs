<template>
    <section>
        <div class="container">
            <div class="font-style-italic">
                Artist coaching
            </div>
            <h2>
                Latest Online Courses
            </h2>
            <div class="shop-courses">
                <ul class="courses-list am-flex">
                    <li class="card">
                        <div class="course">
                            <img src="../assets/img/artist-course-01-480x480.jpg" alt="Course">
                            <div class="course-text">
                                <div class="price">
                                    $18.00
                                </div>
                                <div class="title">
                                    <h3>
                                        <a href="#">The Acrylic Painting Academy</a>
                                    </h3>
                                </div>
                                <div class="info">
                                    <span class="lessons"><i class="fa-regular fa-file-lines"></i> 4 Lessons</span>
                                    <span class="students"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </li>

                    <li class="card">
                        <div class="course">
                            <img src="../assets/img/artist-course-02-480x480.jpg" alt="Course">
                            <div class="course-text">
                                <div class="price">
                                    $21.00
                                </div>
                                <div class="title">
                                    <h3>
                                        <a href="#">Drawing and Shading: Complete Course</a>
                                    </h3>
                                </div>
                                <div class="info">
                                    <span class="lessons"><i class="fa-regular fa-file-lines"></i> 14 Lessons</span>
                                    <span class="students"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </li>

                    <li class="card">
                        <div class="course">
                            <img src="../assets/img/artist-course-03-480x480.jpg" alt="Course">
                            <div class="course-text">
                                <div class="price">
                                    $19.00
                                </div>
                                <div class="title">
                                    <h3>
                                        <a href="#">The Color Theory for Digital Artist</a>
                                    </h3>
                                </div>
                                <div class="info">
                                    <span class="lessons"><i class="fa-regular fa-file-lines"></i> 7 Lessons</span>
                                    <span class="students"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </li>

                    <li class="card">
                        <div class="course">
                            <img src="../assets/img/artist-course-04-480x480.jpg" alt="Course">
                            <div class="course-text">
                                <div class="price">
                                    $35.00
                                </div>
                                <div class="title">
                                    <h3>
                                        <a href="#">Ultimate Guide to Digital Sketching for Beginner</a>
                                    </h3>
                                </div>
                                <div class="info">
                                    <span class="lessons"><i class="fa-regular fa-file-lines"></i> 14 Lessons</span>
                                    <span class="students"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </li>

                    <li class="card">
                        <div class="course">
                            <img src="../assets/img/artist-course-05-480x480.jpg" alt="Course">
                            <div class="course-text">
                                <div class="price">
                                    $19.00
                                </div>
                                <div class="title">
                                    <h3>
                                        <a href="#">Portrait Drawing The Smart Way</a>
                                    </h3>
                                </div>
                                <div class="info">
                                    <span class="lessons"><i class="fa-regular fa-file-lines"></i> 2 Lessons</span>
                                    <span class="students"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </li>

                    <li class="card">
                        <div class="course">
                            <img src="../assets/img/artist-course-06-480x480.jpg" alt="Course">
                            <div class="course-text">
                                <div class="price">
                                    $19.00
                                </div>
                                <div class="title">
                                    <h3>
                                        <a href="#">Mastering Watercolor Painting from Beginner</a>
                                    </h3>
                                </div>
                                <div class="info">
                                    <span class="lessons"><i class="fa-regular fa-file-lines"></i> 9 Lessons</span>
                                    <span class="students"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </li>

                    <li class="card">
                        <div class="course">
                            <img src="../assets/img/artist-course-07-480x480.jpg" alt="Course">
                            <div class="course-text">
                                <div class="price">
                                    $25.00
                                </div>
                                <div class="title">
                                    <h3>
                                        <a href="#">The Art & Science of Drawing</a>
                                    </h3>
                                </div>
                                <div class="info">
                                    <span class="lessons"><i class="fa-regular fa-file-lines"></i> 4 Lessons</span>
                                    <span class="students"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </li>

                    <li class="card">
                        <div class="course">
                            <img src="../assets/img/artist-course-08-480x480.jpg" alt="Course">
                            <div class="course-text">
                                <div class="price">
                                    $22.00
                                </div>
                                <div class="title">
                                    <h3>
                                        <a href="#">The Colored Pencil Drawing Course</a>
                                    </h3>
                                </div>
                                <div class="info">
                                    <span class="lessons"><i class="fa-regular fa-file-lines"></i> 6 Lessons</span>
                                    <span class="students"><i class="fa-regular fa-user"></i> 50 Students</span>
                                </div>
                            </div>
                        </div>
                    </li>




                    <!-- <li class="card" v-for="(element, index) in coursesList" :key="index">
                        <div class="course">
                            <img :src="`../assets/img/${element.image}`" alt="Course">
                            <div class="course-text">
                                <div class="price">
                                    ${{element.price}}
                                </div>
                                <div class="title">
                                    <h3>
                                        <a href="#">{{element.title}}</a>
                                    </h3>
                                </div>
                                <div class="info">
                                    <span class="lessons"><i class="fa-regular fa-file-lines"></i> {{element.lessons}} Lessons</span>
                                    <span class="students"><i class="fa-regular fa-user"></i> {{element.students}} Students</span>
                                </div>

                            </div>

                        </div>
                    </li> -->

                </ul>

                <button class="btn btn-secondary">
                    Get started today
                </button>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "SectionShop",
    props: {
        coursesList: Array,
    }

}
</script>

<style lang="scss" scoped>
@import '../assets/style/variables.scss';

.courses-list {
    flex-wrap: wrap;
    .card {
        width: 25%;

        .course {
            margin: 20px;

            .course-text {
                width: 90%;
                padding: 25px;
                position: relative;

                &:hover {
                    position: relative;
                    background-color: white;
                    border: 2px solid $color_orange;
                    top: -30px;
                    left: 0;

                }

                .price {
                    color: $color_orange;
                    font-weight: 700;
                }

                h3 a {
                    color: initial;
                    text-decoration: none;

                    &:hover {
                        color: $color_orange;
                    }
                }

                .info {
                    font-size: 15px;
                    color: darkgray;
                    span {
                        margin-right: 20px;
                    }
                }
            }
        }     
    }
}

button {
    margin: 0 auto;
    display: block;
}
</style>