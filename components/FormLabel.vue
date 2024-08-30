<script setup>
defineProps({
    label: {
        default: "Label",
        type: String
    }
})
</script>

<template>
    <div class="label">
        <label for="name" class="label-text">{{ label }}</label>
    </div>
</template>