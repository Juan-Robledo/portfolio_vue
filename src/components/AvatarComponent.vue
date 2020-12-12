<template>
    <img :src='picture' alt="Juan Robledo" class="avatar">
</template>

<script>
export default {
    name: 'AvatarComponent',
    props: {
        picture: Image
    }
}
</script>

<style>
    .avatar{
        width: 250px;
        border-radius: 50%;
        display: flex;
        margin: 10px auto;
    }
</style>