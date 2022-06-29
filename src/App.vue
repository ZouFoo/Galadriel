<template>
    <div id="app">
        <div id="background"></div>
        <!-- <Navigation></Navigation> -->
        <router-view/>
    </div>
</template>

<script>
    // @ is an alias to /src
    // import Navigation from './components/Navigation.vue'

    export default {
        name: 'home',
        components: {
            // Navigation
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

    #background {
        background: url("./assets/background.jpg") no-repeat;
        background-position: center;
        height: 100%;
        width: 100%;
        background-size: cover;
        position: fixed;
    }
</style>
