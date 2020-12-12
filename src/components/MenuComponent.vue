<template>
    <div>
        <div class="menu_bar">
            <i class="fas fa-bars"></i>
                <div class="menu">
                    <router-link to='/'>Home</router-link>
                    <router-link to='/about'>About</router-link>
                    <router-link to='/tools'>Tools</router-link>
                    <router-link to='/courses'>Education</router-link>
                </div>
            <!-- <button class="btn_close"><i class="fas fa-times"></i></button> -->
        </div>
    </div>
</template>

<script>
export default {
    name: 'MenuComponent'
}
</script>

<style scoped>
    .menu_bar i{
        font-size: 2rem;
        width: 100%;
        text-align: right;
    }
    .menu{
        display: none;
    }
    .menu a{
        text-decoration: none;
        color: aquamarine;
        width: 100%;
        text-align: center;
    }
    .menu_bar:hover .menu{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color: #999999;
    }
</style>