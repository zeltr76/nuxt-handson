<template>
    <div>
        <header>
            <NuxtLink to="/products">Nuxt Hands-on Products</NuxtLink>
        </header>
    </div>

    <!-- Start of Content -->
    <div>
        <slot />
    </div>

    <!-- Start of Footer -->
    <footer>
        <ul>
            <li><NuxtLink to="/">Home</NuxtLink></li>
            <li><NuxtLink to="/about">About</NuxtLink></li>
            <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
    </footer>
</template>

<style scoped>
    .router-link-exact-active {
        color: red;
    }
</style>