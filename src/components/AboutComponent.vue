<template>
    <div class="about_component">
        <p>{{message}}</p>
    </div>
</template>

<script>
export default {
    name: 'AboutComponent',
    props: {
        message: String
    }
}
</script>

<style>
    .about_component{
        height: 55vh;
    }
</style>