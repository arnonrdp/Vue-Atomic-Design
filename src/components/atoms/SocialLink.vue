<template>
  <a :href="to" class="social-link" target="_blank">
    <img :src="iconPath" :alt="name" />
  </a>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  props: {
    name: { type: String, required: true },
    icon: { type: String, required: true },
    to: { type: String, required: true }
  },
  computed: {
    iconPath(): string {
      return require(`@/assets/images/icons/${this.icon}`)
    }
  }
})
</script>

<style lang="scss" scoped>
.social-link {
  align-items: center;
  background-color: #ff895f;
  border-radius: 5rem;
  display: grid;
  height: 47px;
  justify-items: center;
  transition: transform 0.2s linear;
  width: 47px;
  &:hover {
    transform: scale(1.1);
  }
  img {
    width: 23px;
    height: 23px;
  }
}
</style>
