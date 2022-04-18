<template>
  <div class="component">
    <NavBar />
    <SearchForm />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { NavBar, SearchForm } from '@/components/molecules'

export default defineComponent({
  components: { NavBar, SearchForm }
})
</script>

<style lang="scss" scoped>
.component {
  width: 300px;
}
</style>
