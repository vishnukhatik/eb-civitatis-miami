<template>
  <v-app>
    <v-main>
      <top-bar />
      <nav-bar />
      <v-container>
        <nuxt />
      </v-container>
    </v-main>
    <v-footer :absolute="!fixed" app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>
<script>
import topBar from '@/components/header/topbar.vue'
import navBar from '@/components/header/navbar.vue'
export default {
  components: {
    topBar,
    navBar,
  },
  data() {
    return {
      fixed: false,
    }
  },
}
</script>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

body,
html {
  font-family: Montserrat, arial, sans-serif !important;
}
</style>
