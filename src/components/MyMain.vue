<template>
    <main>
        <SectionJumbotron/>

        <SectionServices/>

        <SectionTestimonials/>

        
    </main>
</template>

<script>
import SectionJumbotron from './SectionJumbotron.vue';
import SectionServices from './SectionServices.vue';
import SectionTestimonials from './SectionTestimonials.vue';

export default {
    name: "MyMain",
    components: {
    SectionJumbotron,
    SectionServices,
    SectionTestimonials
}
}
</script>