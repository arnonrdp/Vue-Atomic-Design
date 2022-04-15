<template>
  <Logo />
  <nav class="nav-bar">
    <NavItem text="Serviços" to="/services" />
    <NavItem text="Sobre mim" to="/about" />
    <NavItem text="Cases" to="/cases" />
    <NavItem text="Contato" to="/contact" />
  </nav>
</template>

<script>
import { defineComponent } from 'vue'
import { Logo, NavItem } from '@/components/atoms'

export default defineComponent({
  components: { Logo, NavItem }
})
</script>

<style lang="scss" scoped>
.nav-bar {
  display: grid;
  grid-auto-flow: column;
  grid-gap: 2rem;
  width: max-content;
}
</style>
