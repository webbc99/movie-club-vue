<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
    <header>
        <h1 id="nav-title">MOVIE CLUB</h1>
        <nav>
            <ul>
                <li><RouterLink to="/about">About</RouterLink></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>

header {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 0 50px;
    box-shadow: 0 1px 8px #ddd;
    background-color: darkslategray;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    color: white;
}

header li {
    list-style: none;
    display: inline-block;
    padding: 0 20px;
}

header a {
    text-decoration: none;
    color: white;
    transition: all 0.5s ease 0s;
}

header a:hover {
    color: #b2bfdb;
}

#nav-title {
    margin-right: auto;
    font-size: 1.5em;
}
</style>