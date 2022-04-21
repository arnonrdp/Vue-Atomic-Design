<template>
  <div class="component">
    <Header />
    <Presentation />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Header, Presentation } from '@/components/organisms'

export default defineComponent({
  components: { Header, Presentation }
})
</script>

<style lang="scss" scoped>
// .component {
//   width: 5rem;
// }
</style>
