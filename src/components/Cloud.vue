<script setup lang="ts">
defineOptions({
    inheritAttrs: true
})

defineProps({
    words: {
        type: Array,
        default: []
    },
    spacing: {
        type: String,
        default: 'p-1'
    },
    color: {
        type: String,
        default: 'bg-primary-subtle'
    },
    text: {
        type: String,
        default: 'text-dark'
    }
})
</script>

<template>
    <div  v-bind="$attrs">
        <span class="badge m-1" :class="[spacing, color, text]" v-for="word in words">{{word}}</span>
    </div>
</template>

