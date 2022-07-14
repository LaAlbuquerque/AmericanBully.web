<template>
    <div class="card">
        <img :src="imagem" alt="">
        <div class="conteudo">
            <strong>{{titulo}}</strong>
            <p>{{texto}}</p>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        imagem: String,
        titulo: String,
        texto: String 
    }
}
</script>

<style>
.card {
    background-color: transparent;
    box-shadow: 0px 1px 4px 1px black;
    width: 500px;
    height: 250px;
    border-radius: 20px;
    display: flex;
    margin: 15px;
}

.card img {
    width: 400px;
    height: 240px;
    padding: 6px;
}

.conteudo {
    padding: 20px;
    width: 100%;
    text-align: center;

}

.conteudo strong {
    font-size: 20px;
}

</style>