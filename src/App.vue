<template>
  <div class="component">
    <SocialNetworks />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialNetworks } from '@/components/molecules'

export default defineComponent({
  name: 'App',
  components: { SocialNetworks }
})
</script>

<style lang="scss">
.component {
  width: 300px;
  margin: 5rem;
}
</style>
