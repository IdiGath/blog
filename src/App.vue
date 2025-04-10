<script setup lang="ts">
import { RouterView } from 'vue-router'
import HeaderView from './views/HeaderView.vue'
import FooterView from './views/FooterView.vue'
</script>

<template>
  <div class="flex flex-col min-h-screen bg-amber-100">
    <HeaderView class="bg-green-700 text-white text-shadow-amber-950 text-outline h-16" />
    <RouterView class="flex-grow" />
    <FooterView class="bg-amber-800 text-black h-24" />
  </div>
</template>
