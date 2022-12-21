<script>
//importo tutti i componenti utili alla creazione della pagina
import AppFooter from './components/AppFooter.vue';
import AppHeader from './components/AppHeader.vue';
import Service from './components/Service.vue';
import WorkWiUs from './components/WorkWiUs.vue';

export default {
  //definisco i componenti che utilizzerò
  components: {
    AppFooter,
    AppHeader,
    Service,
    WorkWiUs
  }
}

</script>

<template>

<AppHeader />

<main>

  <Service />

  <WorkWiUs />

</main>

<AppFooter/>

</template>

<style lang="scss" scoped>
</style>
