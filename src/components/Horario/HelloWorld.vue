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
   <div class="container">
    <h2 class="text-center">{{ bienvenida }}</h2>
    <div class="row">
      <div class="cold-md-6">
        <h6>{{ nombre }}</h6>
        <h6>{{ apellidos }}</h6>

      </div>
    </div>
  </div>
  
</template>

<style scoped></style>
