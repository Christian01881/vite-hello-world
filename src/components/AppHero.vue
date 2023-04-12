<template>
    <div class="hero">
        <h3>{{ heroContent }}</h3>
        <img src="../assets/logo.svg" alt="">
    </div>
</template>

<script>
    export default {
        name: 'AppHero',
        data(){
            return{
                heroContent: 'Benvenuto nella landa della disperazione di node.js'
            }
        }
    }
</script>

<style lang="scss" scoped>


</style>