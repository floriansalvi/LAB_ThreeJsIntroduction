<script setup lang="ts">
import { RouterView } from 'vue-router'
import TheHeader from './components/TheHeader.vue';
import TheFooter from './components/TheFooter.vue';
</script>

<template>
  <TheHeader/>
  <main>
    <router-view />
  </main>
  <TheFooter/>
</template>