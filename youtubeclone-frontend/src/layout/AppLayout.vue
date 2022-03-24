<template>
  <div>
    <AppHeader />
    <AppSidebar />
    <router-view />
  </div>
</template>

<script lang="ts">
import AppHeader from './AppHeader.vue'
import AppSidebar from './AppSidebar.vue'

import { defineComponent } from 'vue'

export default defineComponent({
  components: {
    AppHeader,
    AppSidebar
  }
})
</script>
