<template>
  <div class="services">
    <Service
      title="Front-End"
      description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum condimentum posuere purus, sit amet mollis dolor pulvinar eget. Suspendisse condimentum ipsum sit amet efficitur porta."
    />

    <Service
      title="Back-End"
      description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum condimentum posuere purus, sit amet mollis dolor pulvinar eget. Suspendisse condimentum ipsum sit amet efficitur porta."
    />

    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum condimentum posuere purus, sit amet mollis dolor pulvinar eget. Suspendisse condimentum ipsum sit amet efficitur porta."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
