<script setup>
defineProps({
    label: String,
    name: String,
})
</script>

<template>
    <input type="file" :name="name" :id="name" class="file-input file-input-bordered">
</template>