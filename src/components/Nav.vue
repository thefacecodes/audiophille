<template>
    <nav>
       <img src="../assets/shared/desktop/logo.svg" alt="">
       <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/">Headphones</router-link></li>
        <li><router-link to="/">Speaker</router-link></li>
        <li><router-link to="/">Earphones</router-link></li>
       </ul>
       <img src="../assets/shared/desktop/icon-cart.svg" alt="">
    </nav>
</template>

<script>
export default {
    name: "NavBar"
}
</script>

<style scoped>
nav {
    background: black;
    display:flex;
    justify-content: space-between;
    align-items: center;
    padding: 2em 15em;
    /* position: fixed; */
    width: 100%;
}

nav ul li {
    display: inline;
    text-transform: uppercase;
    padding: 2em;
    font-size: 1.3em;
    font-weight: 700;
}

a {
    text-decoration: none;
    color: white;
}
</style>