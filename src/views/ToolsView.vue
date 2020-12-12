<template>
    <tools-component :tools="tools"></tools-component>
</template>

<script>
import ToolsComponent from '../components/ToolsComponent.vue'
export default {
    name: 'ToolsView',
    components: {
        ToolsComponent
    },
    data() {
        return {
            tools: {
                html: 'HTML',
                css: 'CSS',
                javascript: 'JavaScript',
                vue: 'Vue.js',
                github: 'Github',
                vercel: 'Vercel'
            }
        }
    },
}
</script>

<style>

</style>