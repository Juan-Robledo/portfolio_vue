<template>
    <courses-component class="courses" :titles='titles' />
</template>

<script>
import CoursesComponent from '../components/CoursesComponent'
export default {
    name: 'Courses',
    components: {
        CoursesComponent
    },
    data() {
        return {
            titles: [
                'Programacion Web Full-Stack Completado',
                'Vue.Js Cursando'
            ],
        }
    },
}
</script>

<style>
    @media screen and (min-width: 769px) and (max-width: 1440px) {
        .courses{
            width: 1024px;
            margin: auto;
            height: 350px;
        }
    }
</style>