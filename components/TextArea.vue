<script setup>
defineProps({
    label: String,
    name: String,
    rows: {
        default: "8",
        type: String
    }
})
</script>

<template>
    <textarea :name="name" :id="name" class="textarea textarea-bordered" :rows="rows" </textarea>
</template>