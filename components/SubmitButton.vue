<script setup>
defineProps({
    title: {
        default: "Submit",
        type: String
    }
})
</script>

<template>
    <button type="submit" class="btn btn-sm btn-success text-white w-full lg:w-20">
        {{ title }}
    </button>
</template>