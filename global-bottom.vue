<template>
    <Scroll />
    <footer class="current-slide-indicator">
        <small>
            <SlideCurrentNo />&nbsp;/
            <SlidesTotal />
        </small>
    </footer>
</template>

<style>
.current-slide-indicator {
    position: fixed;
    bottom: 1.2rem;
    left: 3.5rem;
}
</style>