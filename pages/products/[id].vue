<template>
    <div>
        <p>Product Details {{ id }}</p>
    </div>
</template>
<script setup>
const { id } = useRoute().params
</script>