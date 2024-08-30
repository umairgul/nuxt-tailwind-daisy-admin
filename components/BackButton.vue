<script setup>
defineProps({
    href: String
})
</script>

<template>
    <NuxtLink :to="href" class="btn btn-sm btn-neutral text-gray-100">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
            class="size-4">
            <path stroke-linecap="round" stroke-linejoin="round" d="M6.75 15.75 3 12m0 0 3.75-3.75M3 12h18" />
        </svg>
    </NuxtLink>
</template>