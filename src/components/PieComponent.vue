<template>
    <div class="pie">
        <h3>Contact</h3>
        <a href="whatsapp"><i class="fab fa-whatsapp"></i> Whatsapp</a>
        <a href="instagram"><i class="fab fa-instagram"></i> Instagram</a>
        <a href="twitter"><i class="fab fa-twitter"></i> Twitter</a>
        <a href="github"><i class="fab fa-github"></i> Github</a>
        <a href="linkedin"><i class="fab fa-linkedin-in"></i> Linkedin</a>
    </div>
</template>

<script>
export default {
    name: 'PieComponent',
    data() {
        return {
            whatsapp: 'https://wa.link/gn7900',
            instagram: 'https://www.instagram.com/robledojmutn/',
            twitter: 'https://twitter.com/JuanmaRobled',
            github: 'https://github.com/Juan-Robledo',
            linkedin: 'https://www.linkedin.com/in/juan-manuel-robledo-18bbab9b/'
        }
    },
}
</script>

<style scoped>
    .pie{
        width: 100%;
        height: 225px;
        background-color: #2E3140;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    h3{
        margin: 0;
        color: #D97855;
        font-size: 1.7rem;
    }
    a{
        color:#F2A950;
        text-decoration: none;
        padding: 5px 0;
        font-size: 1.3rem;
    }
</style>