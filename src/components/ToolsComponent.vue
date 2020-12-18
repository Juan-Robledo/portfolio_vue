<template>
    <div class="tools">
        <h2 class="subtitle">Tools</h2>
        <ul v-for="(tool, index) in tools" :key="index">
            <li>{{tool}}</li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'ToolsComponent',
    props: {
        tools: String
    }
}
</script>

<style>
    .tools .subtitle{
        text-align: center;
        font-size: 2rem;
    }
    .tools ul{
        padding: 0;
        text-align: center;
        font-size: 1.3rem;
    }
</style>