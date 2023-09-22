<template>
    <div>
        <header>
            <NuxtLink to="/">Nuxt Hands-on</NuxtLink>
            <nav>
                <ul>
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/about">About</NuxtLink></li>
                    <li><NuxtLink to="/products">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>
    </div>

    <!-- Start of content -->
    <div>
        <slot />
    </div>
</template>

<style scoped>
    .router-link-exact-active {
        color: red;
    }
</style>