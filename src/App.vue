<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Sidebar from './components/Sidebar.vue'
</script>

<template>
  <!--<RouterView />-->

  <div class="grid grid-rows-12 grid-cols-12 gap-1 bg-red-300 h-screen">
    <div class="col-span-2 row-span-12 bg-green-200"><Sidebar /></div>
    <div class="col-span-10 row-span-11 bg-green-200"><Header /></div>
    <div class="col-span-10 row-span-11 bg-green-200""><Main /></div>
  </div>
</template>
