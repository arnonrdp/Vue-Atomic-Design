<template>
  <div class="component">
    <NavBar />
    <SearchForm />
    <SocialNetworks />
    <Service
      title="Front-End"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illo nostrum corrupti iste quam rem et fugit accusantium dolor atque laborum dolorem est, officia quisquam praesentium vel inventore, saepe sequi vero!"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { NavBar, SearchForm, SocialNetworks, Service } from '@/components/molecules'

export default defineComponent({
  components: { NavBar, SearchForm, SocialNetworks, Service }
})
</script>

<style lang="scss" scoped>
.component {
  width: 300px;
}
</style>
