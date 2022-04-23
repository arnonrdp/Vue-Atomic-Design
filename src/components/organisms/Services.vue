<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima beatae enim tenetur, dicta id tempore asperiores iste quasi aliquid, veniam consequuntur ratione nulla incidunt maxime sunt nostrum rem quis! Eos."
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima beatae enim tenetur, dicta id tempore asperiores iste quasi aliquid, veniam consequuntur ratione nulla incidunt maxime sunt nostrum rem quis! Eos."
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima beatae enim tenetur, dicta id tempore asperiores iste quasi aliquid, veniam consequuntur ratione nulla incidunt maxime sunt nostrum rem quis! Eos."
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
  grid-gap: 5rem;
  grid-template-columns: repeat(3, 1fr);
}
</style>
