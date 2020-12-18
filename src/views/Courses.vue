<template>
    <courses-component
    :titles='titles' />
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

</style>