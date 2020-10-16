<template>
    <div>
        <nav-bar class="home-navbar">
            <div slot="center">蘑菇街</div>
        </nav-bar>
        <h1>home</h1>
    </div>
</template>

<script>
    import NavBar from "components/common/navbar/NavBar";
    export default {
        name: "Home",
        components: {
            NavBar
        }
    }
</script>

<style scoped>
    .home-navbar{
        background-color: var(--color-text);
        color: var(--color-background);
    }
</style>