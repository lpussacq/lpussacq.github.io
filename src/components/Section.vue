<script setup lang="ts">
defineProps({
    title: String
})
</script>

<template>
    <div>
        <h6 >{{ title }}</h6>
        <div>
            <slot></slot>
        </div>
    </div>
</template>
