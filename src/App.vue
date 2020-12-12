<template>
  <div>
    <encabezado-component></encabezado-component>
    <div>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
    <pie-component></pie-component>
  </div>
</template>

<script>
import EncabezadoComponent from './components/EncabezadoComponent'
import PieComponent from './components/PieComponent.vue'
export default {
    name: 'App',
    components: {
      EncabezadoComponent,
      PieComponent
    },
}
</script>

<style>
  body{
    margin: 0;
  }
</style>
