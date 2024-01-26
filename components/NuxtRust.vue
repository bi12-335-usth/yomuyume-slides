<template>
    <div class="container">
        <img src="/nuxt.svg">
        <img src="/rust.svg">
    </div>
</template>

<style>
.container {
    display: grid;
    grid-template-columns: 1fr 1fr;
}

.container img {
    width: 100%;
    height: auto;
    margin-top: auto;
    margin-bottom: auto;
    padding: 2rem;
}

.glow {
    -webkit-box-shadow: 0px 0px 26px 1px rgba(45, 255, 196, 0.9);
    -moz-box-shadow: 0px 0px 26px 1px rgba(45, 255, 196, 0.9);
    box-shadow: 0px 0px 26px 1px rgba(45, 255, 196, 0.9);
    background-color: transparent;
}
</style>