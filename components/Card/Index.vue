<script setup></script>

<template>
    <div class="card bg-base-100 w-full">
        <div v-if="$slots.figure" class="card-header">
            <figure>
                <slot name="figure"></slot>
            </figure>
        </div>
        <div class="card-body">
            <div v-if="$slots.header" class="card-header">
                <div class="header flex items-center justify-between">
                    <slot name="header"></slot>
                </div>
            </div>
            <slot></slot>
        </div>
    </div>
</template>