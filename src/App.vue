<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HeaderComponent from './components/HeaderComponent.vue';
// import HelloWorld from '@/components/HelloWorld.vue'
</script>

<template>
<div class="font-clashDisplay overflow-x-hidden">
    <HeaderComponent></HeaderComponent>
  
    <RouterView />
</div>
</template>
