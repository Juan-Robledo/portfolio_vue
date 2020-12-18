<template>
    <div class="courses_component">
        <h2 class="subtitle">Education</h2>
        <h3>Cursos en doctadevs</h3>
        <span v-for="(title, index) in titles" :key="index">{{title}}</span>
    </div>
</template>

<script>
export default {
    name: 'CoursesComponent',
    props: {
        titles: String
    }
}
</script>

<style>
    .courses_component{
        display: flex;
        flex-direction: column;
        margin: 15px;
    }
    .courses_component .subtitle{
        text-align: center;
        font-size: 2rem;
    }
    .courses_component h3{
        font-size: 1.7rem;
    }
    .courses_component span{
        font-size: 1.3rem;
        padding: 5px 0;
    }
</style>