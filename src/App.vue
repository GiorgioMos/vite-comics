<script>
import AppHeader from './components/Header.vue'
import AppContent from './components/Content.vue'
import AppIcons from './components/Icons.vue'

export default {
  components: {
    AppHeader,
    AppContent,
    AppIcons,
  }
}
</script>

<template>
  <AppHeader />
  <AppContent />
  <AppIcons />
</template>

<style scoped></style>
