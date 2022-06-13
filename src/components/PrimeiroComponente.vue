<template>
    <div>
        <h1>Olá Vue!</h1>
        <p>Meu nome é {{ nome }}, minha profissão é {{ profissao }}</p>
    </div>
</template>

<script>
    export default{
        name: 'PrimeiroComponente',
        data() {
            return {
                nome: "Gabriela",
                profissao: "Desenvolvedora Frontend"
            }
        }
    }
</script>