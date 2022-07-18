<template>
    <section class="jumbotron">
        <div class="container">
            <div class="content-jumbo am-flex">
                <div>Colonna 1</div>
                <div class="cta-jumbo">
                    Colonna 2
                </div>
                <div>Colonna 3</div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "MyJumbotron",
}
</script>

<style lang="scss" scoped>
@import '../assets/style/variables.scss';
.jumbotron {
    background-color: $brand_primary_color;
    padding: 30px 0;

    .content-jumbo {
        justify-content: space-between;
    }
}
</style>