<template>
  <div class="component">
    <SocialLink
      name="Facebook"
      to="http://www.facebook.com"
      icon="facebook.svg"
    />
    <SocialLink
      name="Github"
      to="http://www.Github.com"
      icon="github.svg"
    />
        <SocialLink
      name="Twitter"
      to="http://www.Twitter.com"
      icon="twitter.svg"
    />
    
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLink } from '@/components/atoms'

export default defineComponent({
  name: 'App',
  components: { SocialLink }
})
</script>

<style lang="scss">
.component {
  width: 300px;
}
</style>
