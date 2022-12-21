<script>


export default {
    data() {
        return {
            vociMenu: ["HOME", "PAGES", "PORTFOLIO", "BLOG", "SHOP", "ELEMENTS"]
        }
    },
}
</script>

<template>
    <!-- inizio navbar -->
    <nav>
        <!-- contenitore contente il logo -->
        <div class="logo">
            <a href="#"><img src="/img/logo-sidearea-1.png" alt=""></a>
        </div>

        <!-- contenitore contente voci di menu -->

        <div class="menu">

            <ul>
                <li v-for="menu in vociMenu">
                <a href="#">{{ menu }}</a>
                </li>
                <a href="#"><li><img src="/svg/svg-1.svg" alt=""></li></a>
            </ul>

        </div>

    </nav>

</template>

<style lang="scss" scoped>
nav {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;

    padding: 0 50px;
    height: 50px;
    position: absolute;
    top: 10px;

}

ul {
    list-style: none;
    display: flex;
    gap: 40px;
}

a{
    text-decoration: none;
    color: black;
}
a:hover{
    color: red;
}
</style>
