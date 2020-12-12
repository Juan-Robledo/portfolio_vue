<template>
  <div>
    <encabezado-component></encabezado-component>
    <menu-component></menu-component>
    <router-view/>
    <pie-component></pie-component>
  </div>
</template>

<script>
import EncabezadoComponent from './components/EncabezadoComponent'
import MenuComponent from './components/MenuComponent.vue'
import PieComponent from './components/PieComponent.vue'
export default {
    name: 'App',
    components: {
      EncabezadoComponent,
      PieComponent,
      MenuComponent
    },
}
</script>

<style>
  body{
    margin: 0;
  }
</style>
