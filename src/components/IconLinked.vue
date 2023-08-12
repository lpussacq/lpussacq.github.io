<script setup lang="ts">
defineProps({
    icon: String,
    link: String,
    value: String
})
</script>

<template>
    <div class="d-flex bg-secondary border border-dark-subtle rounded">
        <div class="p-2 bg-dark rounded-start d-flex align-items-center">
            <i class="bi" :class="icon"></i>
        </div>
        <div class="p-2">
            <a :href="link">{{ value }}</a>
        </div>
    </div>
</template>

<style scoped>
a, a:visited {
    color: var(--bs-gray-100);
}
</style>