<template>
    <div class="container">
        <div class="footer-main am-flex">
            <div class="info-contact">
                <h4>Adress</h4>
                <div>
                    382 NE 191st St # 87394 Miami, FL 33179-3899
                </div>
                <div>
                    +1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)
                </div>
                <div>
                    support@maxcoach.com
                </div>
                <!-- Social -->
                <div class="social">
                    <ul class="am-flex">
                        <li v-for="(element, index) in iconSocialtwo" :key="index">
                            <a :href="element.url"><img :src="element.icon" :alt="element.text_alt"></a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="menu-one">
                <h4>Explore</h4>
                <ul>
                    <li v-for="(element, index) in menuOne" :key="index">
                        <a :href="element.url">{{element.text}}</a>
                    </li>
                </ul>

            </div>
            <div class="menu-two">
                <h4>Information</h4>
                <ul>
                    <li v-for="(element, index) in menuTwo" :key="index">
                        <a :href="element.url">{{element.text}}</a>
                    </li>
                </ul>
            </div>
            <div class="ig-social">
                <h4>
                    Instagram <span class="profile-ig"><a href="#">@maxcoach</a></span>
                </h4>
                <div class="ig-gallery am-flex">

                    <div class="card-gallery">
                        <a href="#"><img src="../assets/img/120084500_197897808368764_8114555493043279565_n.jpg" alt="Immagine"></a>
                    </div>
                    <div  class="card-gallery">
                        <a href="#"><img src="../assets/img/120012142_177596140500760_8623485824101406058_n.jpg" alt="Immagine"></a>
                    </div>
                    <div class="card-gallery">
                        <a href="#"><img src="../assets/img/120099363_364334431619755_7198812647386067017_n.jpg" alt="Immagine"></a>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-copy">
            <div>
                &copy; 2020 Maxcoach. All Rights Reserved
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: "MyFooter",
    props: {
        menuOne: Array,
        menuTwo: Array,
        iconSocialtwo: Array
    }
}
</script>

<style lang="scss">
@import '../assets/style/variables.scss';

.footer-main {
    justify-content: space-between;
    font-size: 14px;
    line-height: 1.7;
    padding: 100px 0px 50px 0px;

    .social {
        margin-top: 10px;
    }

    .social li {
        margin: 0 8px;

    }

    .social li img {
        width: 16px;
        height: 16px;
    }

    .info-contact, .ig-social {
        width: 30%;
    }
    .menu-one, .menu-two {
        width: 20%;
    }

    .profile-ig a {
        font-size: 14px;
        text-decoration: none;
        color: orange;
    }
    .card-gallery {
        width: calc(100% / 3);
        display: inline-block;
        background-color: pink;
        margin: 2px;
    }
}

.footer-copy {
    text-align: center;
    padding: 40px 0;
}


</style>