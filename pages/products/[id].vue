<template>
    <div>
        <h1>Hello, this is the Product {{ id }}</h1>
    </div>
</template>

<script setup>
    const { id } = useRoute().params
    
    definePageMeta({
        layout: 'products'
    })
</script>

<style scoped>
    .h1 {
        font-size: 36px;
        margin-bottom: 20px;
    }
</style>