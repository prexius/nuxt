<template>
    <div class="card text-center">
        <img :src="product.image" alt="" class="thumb" />
        <NuxtLink :to="`/products/${product.id}`">
            <p class="font-bold">{{ product.title }}</p>
        </NuxtLink>
    </div>
</template>

<script setup>
const { product } = defineProps(['product'])

</script>

<style scoped></style>