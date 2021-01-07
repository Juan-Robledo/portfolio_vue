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
        position: absolute;
        top: 15%;
    }
    .menu{
        display: none;
        /* height: 200px; */
    }
    .menu a{
        text-decoration: none;
        color:#D97855;
        font-size: 1.3rem;
        padding: 5px;
    }
    .menu_bar:hover .menu{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color: #2E3140;
    }
    @media screen and (min-width: 769px) and (max-width: 1440px) {
        .menu{
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            padding: 5px 0;
        }
        .menu:hover{
            color: #2E3140;
        }
        i {
            display: none;
        }
    }
</style>