<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HeaderTemplate from './components/Header.vue'
import FooterTemplate from './components/Footer.vue'
</script>

<template>
    <HeaderTemplate/>
    <RouterView />
    <FooterTemplate/>
</template>