<script setup>
    import { defineProps } from 'vue';

    const props = defineProps({
        total: {
            type: Number,
            require: true,
        }
    })


</script>


<template>
    <h2>Your Balance</h2>
    <h1 id="balance">{{ total }}</h1>


</template>