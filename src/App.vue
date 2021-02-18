<template>
  <div class="component">
    <HomeTemplate />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { HomeTemplate } from '@/components/templates'

export default defineComponent({
  name: 'App',
  components: { HomeTemplate }
})
</script>

<style lang="scss">
.component {
}
</style>
