<template>
  <div class="home">
    <avatar-component :picture='picture'></avatar-component>
    <data-component :personalData='personalData'></data-component>
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
      personalData: {
        apellido: 'Robledo',
        nombres: 'Juan Manuel',
        edad: 28,
        telefono: 3512628432,
        email: 'robledojmutn@gmail.com',
      }
    }
  },
}
</script>
