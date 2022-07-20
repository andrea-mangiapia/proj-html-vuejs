<template>
    <main>
        <SectionJumbotron/>

        <SectionServices/>

        <SectionTestimonials/>

        <SectionShop :coursesList="courses"/>

        
    </main>
</template>

<script>
import SectionJumbotron from './SectionJumbotron.vue';
import SectionServices from './SectionServices.vue';
import SectionTestimonials from './SectionTestimonials.vue';
import SectionShop from './SectionShop.vue';
export default {
    name: "MyMain",
    components: {
    SectionJumbotron,
    SectionServices,
    SectionTestimonials,
    SectionShop
    },
    
data() {
    return {
        courses: [
                {
                    image: 'artist-course-01-480x480.jpg',
                    price: '18.00',
                    title: 'The Acrylic Painting Academy',
                    lessons: '4',
                    students: '50',
                },
                {
                    image: 'artist-course-02-480x480.jpg',
                    price: '21.00',
                    title: 'Drawing and Shading: Complete Course',
                    lessons: '14',
                    students: '50',
                },
                {
                    image: 'artist-course-03-480x480.jpg',
                    price: '19.00',
                    title: 'The Color Theory for Digital Artist',
                    lessons: '7',
                    students: '50',
                },
                {
                    image: 'artist-course-04-480x480.jpg',
                    price: '35.00',
                    title: 'Ultimate Guide to Digital Sketching for Beginner',
                    lessons: '14',
                    students: '50',
                },
                {
                    image: 'artist-course-05-480x480.jpg',
                    price: '19.00',
                    title: 'Portrait Drawing The Smart Way',
                    lessons: '2',
                    students: '50',
                },
                {
                    image: 'artist-course-06-480x480.jpg',
                    price: '19.00',
                    title: 'Mastering Watercolor Painting from Beginner',
                    lessons: '9',
                    students: '50',
                },
                {
                    image: 'artist-course-07-480x480.jpg',
                    price: '25.00',
                    title: 'The Art & Science of Drawing',
                    lessons: '4',
                    students: '50',
                },
                {
                    image: 'artist-course-08-480x480.jpg',
                    price: '22.00',
                    title: 'The Colored Pencil Drawing Course',
                    lessons: '6',
                    students: '50',
                },
            ],
    
    }
  }

}
</script>