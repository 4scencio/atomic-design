<template>
  <div class="component">
    <Services title="Front-End" description="lorem ipsum" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Services } from '@/components/molecules'

export default defineComponent({
  name: 'App',
  components: { Services }
})
</script>

<style lang="scss">
.component {
  width: 300px;
  margin: 5rem;
}
</style>
