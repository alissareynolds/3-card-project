<template>
  <div class="home">
    <sedan-component></sedan-component>
    <suv-component></suv-component>
    <luxury-component></luxury-component>
  </div>
</template>

<script>
import SedanComponent from '@/components/SedanComponent.vue'
import SuvComponent from '@/components/SuvComponent.vue'
import LuxuryComponent from '@/components/LuxuryComponent.vue'

export default {
  components: { SedanComponent, SuvComponent, LuxuryComponent },
  name: 'HomeView',
}
</script>

<style scoped>

.home {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

</style>
