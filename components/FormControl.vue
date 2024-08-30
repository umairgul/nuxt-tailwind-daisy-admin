<script setup>
defineProps({
    label: String
})
</script>

<template>
    <div class="form-control mt-2">
        <FormLabel v-if="label" :label="label"/>
        <slot></slot>
    </div>
</template>