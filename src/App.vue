<script setup>
import { ref } from "vue";

const nome = ref('')
const active = ref(true)

</script>

<template>
  <button @click="active = !active">Troca cor</button>
   
  <input v-model="nome" type="text" placeholder="Digite seu nome">

  <p :class="active ? 'blue' : 'red'">Olá, {{nome}}</p>

  <a :href="`https://www.google.com/${id}`">link</a>
    
</template>

<style scoped>
.blue {
  color: blue;
}

.red {
  color: red;
}
</style>
