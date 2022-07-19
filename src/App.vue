<template>
  <div id="app">
    <!-- HEADER -->
      <MyHeader :menuHeader="mainMenu" :iconSocial="social" />

    <!-- MAIN -->
    <MyMain/>

    <!-- FOOTER -->    
    <footer>
      <MyFooter :menuOne="menuExplore" :menuTwo="menuInformation" :iconSocialtwo="social"/>
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

      menuExplore: [
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
      ],

    }
  }

}
</script>

<style lang="scss">
@import './assets/style/common.scss';
@import './assets/style/variables.scss';
@import 'https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css';

@font-face {
  font-family: "Rossela";
  src: local("Rossela"),
  url(./assets/font/Rossela-Demo.ttf) format("truetype");
}

.font-style-italic {
  font-family: "Rossela", Helvetica, Arial;
  font-size: 45px;
  font-weight: 400;
  color: $secondary_text;
  text-align: center;
}
h2 {
  text-align: center;
  padding: 10px 0;
}

.btn {
  padding: 12px 26px;
  margin: 20px 0;
  border-radius: 4px;
  cursor: pointer;

}
.btn-primary {
  background-color: $color_orange;
  border: 1px solid $color_orange;
  color: white;

  &:hover {
    background-color: $color_ice_cold;
    border: 1px solid $color_ice_cold;
  }
}

.btn-secondary {
  background-color: $color_orange_light;
  border: 1px solid $color_orange_light;
  color: $color_orange;

  &:hover {
    background-color: $color_orange;
    border: 1px solid $color_orange;
    color: white;
  }
}



</style>
