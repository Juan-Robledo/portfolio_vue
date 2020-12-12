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
    }
</style>