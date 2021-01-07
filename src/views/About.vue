<template>
    <about-component class="about" :message='message'></about-component>
</template>

<script>
import AboutComponent from '../components/AboutComponent.vue'
export default {
  components: { AboutComponent },
  name: 'About',
  data() {
    return {
      message: 'Hola soy Juan, mucho me dicen cata, tengo 28 años y soy padre soltero. Este año decidí cambiar mí horizonte profesional y encontré la programación web, desde que la ví cambio todo en mí, sentí que es lo que tendría que haber estudiado hace bastante tiempo. Hoy soy nuevo en este mundo informático realizando cursos de web developer full-stack y Vue.js. En mis tiempos libres disfruto de pasar tiempo con mí familia y amigos.'
    }
  },
}
</script>

<style scoped>
  @media screen and (min-width: 769px) and (max-width: 1440px) {
    .about{
      width: 1024px;
      height: 350px;
      margin: auto;
    }
  }
</style>
