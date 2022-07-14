<template>
  <v-app>
    <Cabecario/>
    <HomeVue/>
  </v-app>
</template>

<script>
import Cabecario from './components/commons/Cabecario.vue'
import HomeVue from './views/Home.vue'
export default {
  components: {
    Cabecario,
    HomeVue
  }
}
</script>

<style>

</style>
