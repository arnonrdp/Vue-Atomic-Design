<template>
  <a :href="to" class="nav-item">
    {{ text }}
  </a>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    text: { type: String, required: true },
    to: { type: String, required: true }
  }
})
</script>

<style lang="scss" scoped>
.nav-item {
  color: #293947;
  font-size: 1.3rem;
  text-decoration: none;
}
</style>
