<script setup>
import { ref } from "vue";

const nome = ref('')

</script>

<template>
   
  <input v-model="nome" type="text" placeholder="Digite seu nome">

  <p>Olá, {{nome}}</p>
    
</template>

<style scoped></style>
