<script setup>
import FooterView from './components/FooterView.vue';
import HeaderView from './components/HeaderView.vue';
</script>

<template>
  <HeaderView />

    <main class="min-h-screen">
      <router-view />
    </main>

    <FooterView />
</template>