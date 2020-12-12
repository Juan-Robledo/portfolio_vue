<template>
    <div class="courses_component">
        <h2 class="subtitle">Education</h2>
        <ul v-for="(course, index) in courses" :key="index">
            <li>{{course}}</li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'CoursesComponent',
    props: {
        courses: String
    }
}
</script>

<style>
    .courses_component{
        height: 55vh;
    }
    .courses_component .subtitle{
        text-align: center;
    }
</style>