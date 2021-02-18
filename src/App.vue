<template>
  <div class="component">
    <Presentation />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Presentation } from '@/components/organisms'

export default defineComponent({
  name: 'App',
  components: { Presentation }
})
</script>

<style lang="scss">
.component {
  margin: 5rem;
}
</style>
