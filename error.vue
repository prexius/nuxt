<template>
    <div>
        <h3>{{ error.message }}</h3>
    </div>
</template>

<script setup>
defineProps(['error'])
</script>

<style scoped></style>