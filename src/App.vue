<template>
    <div id="app">
        <Navigation></Navigation>
        <router-view/>
    </div>
</template>

<script>
    // @ is an alias to /src
    import Navigation from './components/Navigation.vue'

    export default {
        name: 'home',
        components: {
            Navigation
        }
    }
</script>

<style>

    #app {
        font-family: 'Avenir', Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
    }
</style>
