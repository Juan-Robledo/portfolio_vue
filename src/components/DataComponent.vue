<template>
    <div class="personal_data">
        <span>Apellido y Nombres: {{`${apellido} ${nombres}`}}</span>
        <span>Edad: {{edad}}</span>
        <span>Telefono: {{telefono}}</span>
        <span>Email: {{email}}</span>
    </div>
</template>

<script>
export default {
    name: 'DataComponent',
    props: {
        apellido: String,
        nombres: String,
        edad: Number,
        telefono: Number,
        email: String
    }
}
</script>

<style>
    .personal_data{
        display: flex;
        flex-direction: column;
        font-size: 1.3rem;
        margin: 15px;
    }
    .personal_data span{
        padding: 5px 0;
    }
    @media screen and (min-width: 769px) and (max-width: 1440px) {
        .personal_data{
            text-align: center;
        }
    }

</style>