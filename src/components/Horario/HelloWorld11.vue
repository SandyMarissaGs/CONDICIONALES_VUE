<script setup>
import{ ref } from 'vue'


defineProps({
 Nombre: String,
})


</script>

<template>

    <h1>{{ Nombre }}</h1>
 
</template>

<style scoped></style>
