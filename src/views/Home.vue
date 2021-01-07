<template>
  <div class="home">
    <avatar-component :picture='picture'></avatar-component>
    <data-component
    :apellido='apellido'
    :nombres='nombres'
    :edad='edad'
    :telefono='telefono'
    :email='email' />
  </div>
</template>

<script>
import AvatarComponent from '../components/AvatarComponent.vue'
import DataComponent from '../components/DataComponent.vue'
// @ is an alias to /src


export default {
  components: {
    AvatarComponent,
    DataComponent,
  },
  name: 'Home',
  data() {
    return {
      picture: 'https://portfolio.juan-robledo.vercel.app/img/profile.95ddbe68.jpeg',
      apellido: 'Robledo',
      nombres: 'Juan Manuel',
      edad: 28,
      telefono: 3512628432,
      email: 'contacto@juanrobledo.com.ar',
    }
  },
}
</script>

<style scoped>
  @media screen and (min-width: 769px) and (max-width: 1440px) {
    .home{
      width: 1024px;
      margin: auto;
    }
  }
</style>