<template>
  <NavbarComponent />
  <DashboardComponent />
</template>

<script>
import NavbarComponent from '../components/NavbarComponent.vue'
import DashboardComponent from '../components/DashboardMainComponent.vue'

export default {
  name: 'DashboardView',
  components: {
    NavbarComponent,
    DashboardComponent
  }
}
</script>

<style>

</style>