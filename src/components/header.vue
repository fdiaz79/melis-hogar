<template>
    <div>
        <div id="app-header">
            <p class="text-center" id="header-text">
                Hogar Geriatrico Melis y Mao: Cra 38A #61-09 - Tel. 57-1-2213950
            </p>
        </div>
        <app-navbar></app-navbar>
    </div>
    
</template>

<script>
    import navbar from './navbar.vue'
    export default {
        components: {
            'app-navbar': navbar
        }
        
    }
</script>

<style scoped>
    #app-header {
        background-color:#1abbb2;
        padding: 2%;
    }
    #header-text {
        color:white;
        font-size: 1.6em;
        font-weight: 600;
        margin-top: 10px;
    }

</style>