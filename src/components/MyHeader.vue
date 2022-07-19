<template>
    <header>
        <!-- Header Top -->
        <div class="header-top">
            <div>
                Starts TOMORROW! Our biggest event of the year.
            </div>
            <div class="countdown">
                <i class="fa-regular fa-clock"></i> 00 : 00 : 00 : 00
            </div>
            <div>
                <button></button>
            </div>
            <div class="btn-1">
                Bottone
            </div>
        </div>
        <!-- Header Main -->
        <div class="container">
            <div class="header-main">
                <div class="logo">
                    <img src="../assets/img/dark-logo.png" alt="Logo MaxCoach">
                </div>
                <nav>
                    <ul class="am-flex">
                        <li v-for="(element, index) in menuHeader" :key="index">
                            <a :href="element.url">{{element.text}}</a>
                        </li>
                    </ul>
                </nav>

                <div class="social">
                    <ul class="am-flex">
                        <li v-for="(element, index) in iconSocial" :key="index">
                            <a :href="element.url"><img :src="element.icon" :alt="element.text_alt"></a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: "MyHeader",
    props: {
        menuHeader: Array,
        iconSocial: Array
    }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/variables.scss';
.header-top {
    background-color: $color_silver;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 10px 0;
    font-size: 14px;

    .countdown {
        font-size: 18px;
        font-weight: 700;
        margin: 0 20px;
    }
}
.header-main {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 80px;

    .logo img {
        width: 155px;
    }
    nav li {
        margin: 0 15px;
    }

    .social li {
        margin: 0 8px;

    }

    .social li img {
        width: 16px;
        height: 16px;
    }
}


</style>