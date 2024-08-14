<script setup>
  function minhaFuncao() {
    alert('Mensagem da Função!')
  }
</script>

<template>
  <button @click="minhaFuncao">Clique Aqui</button>
  <input type="text" @keypress="minhaFuncao">
</template>

<style scoped>

</style>
