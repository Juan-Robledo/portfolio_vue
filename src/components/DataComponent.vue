<template>
    <div class="personal_data">
        <ul v-for="(personal, index) in personalData" :key="index">
            <li>{{personal}}</li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'DataComponent',
    props: {
        personalData: String
    }
}
</script>

<style>
    .personal_data li{
        list-style: none;
        font-size: 1.2rem;
    }
</style>