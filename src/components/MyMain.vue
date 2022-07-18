<template>
    <main>
        <SectionJumbotron/>

        <SectionAbout/>

        <SectionTestimonials/>

        
    </main>
</template>

<script>
import SectionJumbotron from './SectionJumbotron.vue';
import SectionAbout from './SectionAbout.vue';
import SectionTestimonials from './SectionTestimonials.vue';

export default {
    name: "MyMain",
    components: {
    SectionJumbotron,
    SectionAbout,
    SectionTestimonials
}
}
</script>