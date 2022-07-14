<template>
    <header class="cabecario">
        <div class="logo">
            <img src="../../assets/logoA.png" alt="">
            <strong>American Bully</strong>
        </div>
        <div class="espacador"></div>
        <div class="botao">
            <button>Cadastre-se</button>
            <button>Entrar</button>
        </div>    
    </header>
</template>

<script>

</script>

<style>
.cabecario {
    height: 50px;
    background-color: rgb(241 239 233 / 43%);
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    box-shadow: 0px 1px 4px 0px #2e160387;
    display: flex;
    padding: 0 10px;
}
.botao {
    float: right; 
    height: 100%;
    display: flex;
}

.botao button {
    background-color: transparent;
    border: none;
    font-size: 16px;
    font-family: none;
    cursor: pointer;
    margin: 0 5px;
    font-weight: 600;
}

.botao button:hover  {
    border-bottom: 1px solid sienna;
    font-size: 18px;
}

.logo {
    height: 100%;
    display: flex;
}

.logo strong {
    margin: auto;
    margin-left: 10px;
}
.espacador {
    margin-inline-start: auto;
}
</style>
