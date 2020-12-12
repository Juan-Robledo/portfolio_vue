<template>
    <courses-component :courses='courses'></courses-component>
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
            courses: {
                title: ['Programacion Web Full-Stack', 'Vue.Js'],
                stateCourse: ['Completado', 'Cursando']
            }
        }
    },
}
</script>

<style>

</style>