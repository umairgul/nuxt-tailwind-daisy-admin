<script setup>
defineProps({
    name: String,
    type: {
        default: "text",
        type: String
    }
})
</script>

<template>
    <input :type="type" :name="name" :id="name" class="input input-bordered" />
</template>