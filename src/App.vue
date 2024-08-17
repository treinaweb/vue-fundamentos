<script setup>
import { ref } from "vue";

let ehVisivel = ref(false);
function minhaFuncao() {
  ehVisivel.value = !ehVisivel.value;
}
</script>

<template>
    <button @click="minhaFuncao">Clique Aqui</button>

    <p v-if="ehVisivel">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur hic
        cumque culpa aut! Architecto dignissimos fuga id sunt, iste laborum
        assumenda magni non, ipsa aliquam nulla ratione placeat, temporibus
        tempore.
    </p>
    
</template>

<style scoped></style>
