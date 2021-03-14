<template>
    <div id="app">
        <navbar />

        <router-view />

        <footer-comp />

        <apply-to-vacancy-modal />
    </div>
</template>

<script>
    import Navbar from "@/components/Navbar";
    import FooterComp from "@/components/Footer";
    import ApplyToVacancyModal from "@/components/modals/ApplyToVacancyModal";

    export default {
        name: "App",

        components: {
            Navbar,
            FooterComp,
            ApplyToVacancyModal
        }
    }
</script>

<style lang="scss">
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap');

    body {
        padding: 0;
        margin: 0;
    }

    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        color: #2c3e50;
        background: #1A1A1A;
    }
</style>
