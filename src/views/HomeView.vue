<script setup>

import AboutContent from '../components/AboutContent.vue'
import NavigationBar from '../components/NavigationBar.vue'
import HeaderBackground from '../components/HeaderBackground.vue'

</script>

<template>
  <div class="home">
    <NavigationBar />
    <HeaderBackground />
    <AboutContent />
  </div>
</template>

<style scoped>

.home {
  display: flex;
  flex-direction: column;
}

</style>
