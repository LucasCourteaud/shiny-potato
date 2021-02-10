<template>
    <div class="bar">
        <li class="logo">PostApp</li>
        <ul class="nav">
            <li><router-link :to="{name: 'Home'}">Home</router-link></li>
            <li><router-link :to="{name: 'LoginPage'}">Login</router-link></li>
            <li>Signup</li>
        </ul>
    </div>
</template>

<script>
    export default {
    }
</script>

<style lang="scss" scoped>
    .logo {
        font-family: 'Lobster';
        font-size: 60px;
    }
    .nav {
        font-family: 'Impact';
    }
    .bar {
        background-color: #00AEFF;
        color: white;
        display: flex;
        justify-content: space-around;
    }
    .bar li {
        display: inline-block;
        font-size: 40px;
        padding: 30px;
    }
</style>