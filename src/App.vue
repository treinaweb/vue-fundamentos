<script setup>
import { ref } from "vue";

const frutas = ref(["Maçã", "Banana", "Laranja"]);
const novoItem = ref('')

function adicionarNovoItem() {
  frutas.value.push(novoItem.value)
  novoItem.value = ''
}
</script>

<template>
  <input @keyup.enter="adicionarNovoItem" v-model="novoItem" type="text" placeholder="Adicione um novo item">
    <ul>
        <li v-for="fruta in frutas" :key="fruta">
            {{ fruta }}
        </li>
    </ul>
</template>

<style scoped></style>
