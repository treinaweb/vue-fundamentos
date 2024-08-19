<script setup>
const props = defineProps({
    imagem: String,
    nome: String,
    ano: Number,
    descricao: String,
});
</script>

<template>
    <div>
        <img
            :src="props.imagem"
            alt=""
            width="200px"
            height="auto"
        />
        <h2> {{ props.nome }} </h2>
        <h3>{{ props.ano }}</h3>
        <p>{{ props.descricao }}</p>
    </div>
</template>
<style scoped>
h2,
h3,
p {
    margin: 0 0 0.5rem 0;
}
</style>
