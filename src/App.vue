<template>
  <div id="app">
    <sidenav/>
    <navbar/>
    <router-view/>
  </div>
</template>

<script>
import sidenav from '@/components/sidebar.vue';
import navbar from '@/components/navbar.vue'

export default {
  name: 'App',
  components: {
    sidenav,
    navbar
  }
}
</script>

<style>
body{
  background: #F8F8F8;
  font-family: 'Khula', sans-serif;
}
</style>
