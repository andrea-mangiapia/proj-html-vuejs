<template>
  <div id="app">
    <!-- HEADER -->
      <MyHeader :menuHeader="mainMenu" :iconSocial="social" />

    <!-- MAIN -->
    <MyMain/>

    <!-- FOOTER -->    
    <footer>
      <MyFooter/>
    </footer>
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MyMain from './components/MyMain.vue'
import MyFooter from './components/MyFooter.vue'

export default {
  name: 'App',
  components: {
    MyHeader,
    MyMain,
    MyFooter
  },
  data() {
    return {
      mainMenu: [
        {
          text: 'Home',
          url: '#',
        },
        {
          text: 'Pages',
          url: '#',
        },
        {
          text: 'Courses',
          url: '#',
        },
        {
          text: 'Features',
          url: '#',
        },
        {
          text: 'Blog',
          url: '#',
        },
        {
          text: 'Shop',
          url: '#',
        },
      ],

      social: [
        {
          icon: require('./assets/img/twitter.svg'),
          text_alt: 'Twitter',
          url: '#',
        },
        {
          icon: require('./assets/img/facebook.svg'),
          text_alt: 'Facebook',
          url: '#',
        },
        {
          icon: require('./assets/img/black-instagram.svg'),
          text_alt: 'Instagram',
          url: '#',
        },
        {
          icon: require('./assets/img/linkedin-square.svg'),
          text_alt: 'Linkedin',
          url: '#',
        },
      ],

      /* menuExplore: [
        {
          text: 'Start here',
          url: '#',
        },
        {
          text: 'Success story',
          url: '#',
        },
        {
          text: 'Blog',
          url: '#',
        },
        {
          text: 'Courses',
          url: '#',
        },
        {
          text: 'Contact us',
          url: '#',
        },
      ],

      menuInformation: [
        {
          text: 'Membership',
          url: '#',
        },
        {
          text: 'Purchase guide',
          url: '#',
        },
        {
          text: 'Privacy policy',
          url: '#',
        },
        {
          text: 'Terms of services',
          url: '#',
        },
      ], */


    }
  }

}
</script>

<style lang="scss">
@import './assets/style/common.scss'
</style>
