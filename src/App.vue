<script setup>
const nome = "Amauri";
const sobrenome = "Blanco";
const idade = 33;
</script>

<template>
    <p class="texto">{{`O nome do Professor é ${nome} ${sobrenome}, ele tem ${idade} anos`}}</p>
</template>

<style scoped>
  .texto {
    background-color: blue;
    color: black;
  }
</style>
