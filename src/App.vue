<script setup>
import Carro from "./components/Carro.vue";
</script>

<template>
    <section class="carros">
        <Carro
            imagem="https://s2-autoesporte.glbimg.com/UWiWKJtlidgBWLaV7H-oeLuik7A=/0x0:620x400/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_cf9d035bf26b4646b105bd958f32089d/internal_photos/bs/2020/s/k/6GMdJXSQqXVLy4BiL50g/2016-02-22-goldianteira.jpg"
            nome="Gol"
            :ano=2017
            descricao="Carro Popular"
        />
        <Carro
            imagem="https://www.autossegredos.com.br/wp-content/webp-express/webp-images/uploads/2015/06/palio_fire_0001.jpg.webp"
            nome="Palio"
            :ano=2017
            descricao="Carro Popular"
        />
        <Carro
            imagem="https://s2-autoesporte.glbimg.com/r04OvZkB5nl_WMm8UurxzGf2s-c=/0x0:620x400/984x0/smart/filters:strip_icc()/i.s3.glbimg.com/v1/AUTH_cf9d035bf26b4646b105bd958f32089d/internal_photos/bs/2020/6/C/SmxefwT5Gf0ityb9lCng/2016-06-01-fiat-punto-2017.jpg"
            nome="Punto"
            :ano=2017
            descricao="Carro Popular"
        />
    </section>
</template>

<style scoped>
.carros {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px,1fr));
    gap: 2rem;
}
</style>
