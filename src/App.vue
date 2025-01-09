<script setup>
//import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Sidebar from './components/Sidebar.vue'
import HomeView from './views/HomeView.vue'
</script>

<template>
  <div class="grid grid-rows-9 grid-cols-9 bg-red-100 h-dvh">
    <Sidebar/>
    <Header/>
    <Main/>
  </div>
</template>
