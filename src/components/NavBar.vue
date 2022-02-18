<script setup>

</script>

<template>
    <nav>
        <div class="nav-items">
            <a href="/" class="nav-item">Home</a>
            <a href="/" class="nav-item">Projects</a>
            <a href="/" class="nav-item">Resume</a>
            <a href="/" class="nav-item">Contact</a>
            <a href="/" class="nav-item">About</a>
        </div>
    </nav>
</template>

<style lang="css" scoped>
nav {
    background-color: var(--accent-color);
    padding: 1rem;
}

.nav-item {
    text-decoration: none;
    font-size: 1.5rem;
    color: var(--text-color);
}

.nav-items {
    font-family: var(--heading-font);
    font-weight: var(--font-bold);
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
    gap: 1rem;
}
</style>