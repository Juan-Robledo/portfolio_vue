<template>
    <div class="about_component">
        <h2 class="subtitle">About me</h2>
        <p class="message">{{message}}</p>
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
        height: 65vh;
    }
    .about_component .subtitle{
        text-align: center;
        font-size: 2rem;
    }
    .about_component .message{
        margin: 30px;
        font-size: 1.3rem;
    }
</style>