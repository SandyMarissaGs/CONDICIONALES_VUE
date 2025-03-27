<script setup>
import{ ref } from 'vue'

const bienvenida= ref("Bienvenidos a la seccion de condicionales")
const nombre = ref("Sandy Marissa")
const apellidos = ref("Garcia Santiago")

//defineProps({
 // msg: String,
//})

</script>

<template>
  <h2>{{ bienvenida }}</h2>
  
</template>

<style scoped></style>
