<template>
  <div class="component">
    <Header />
    <Presentation />
    <Services />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Header, Presentation, Services } from '@/components/organisms'

export default defineComponent({
  components: { Header, Presentation, Services }
})
</script>

<style lang="scss" scoped>
// .component {
//   width: 5rem;
// }
</style>
