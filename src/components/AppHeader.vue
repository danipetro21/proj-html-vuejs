<script>
//importo tutti i componenti utili alla creazione della pagina
import NavBar from './NavBar.vue';
import JumboTron from './JumboTron.vue';


export default {
    //definisco i componenti che utilizzerĂ˛
    components: {
        NavBar,
        JumboTron
    }
}

</script>

<template>

    <div class="navB">

        <NavBar />

    </div>

    <div class="Cjumbo">

        <JumboTron />
    </div>

</template>

<style lang="scss" scoped>
@use '../style/partials/variables' as *;

.navB {
    width: 100vw;
}

.Cjumbo {
    width: 100vw;
}
</style>
