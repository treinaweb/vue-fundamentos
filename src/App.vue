<script setup>
import { ref } from 'vue';

let numero = ref(0);
console.log(numero)
  function minhaFuncao() {
    numero.value = numero.value + 1;
  }
</script>

<template>
  <button @click="minhaFuncao">Clique Aqui</button>
  {{ numero }}
</template>

<style scoped>

</style>
