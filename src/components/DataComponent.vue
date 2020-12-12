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

</style>