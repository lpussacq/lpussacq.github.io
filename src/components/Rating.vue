<script setup lang="ts">
defineProps({
    rate: {
        type: Number,
        default: 5
    }
})
</script>

<template>
    <div class="d-flex">
        <div class="p-1" v-for="i in 5">

            <i class="bi" :class="{
                'bi-star-fill': rate-(i-1) >= 1, 
                'bi-star-half': rate-(i-1) == 0.5, 
                'bi-star': rate-(i-1) < 0.5
            }"></i>
        </div>
    </div>
</template>