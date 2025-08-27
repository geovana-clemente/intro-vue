<script setup>
const produtos = [
    { nome: 'Carro', preco: 2000, categoria: 'Veículo' },
    { nome: 'Moto', preco: 1000, categoria: 'Veículo' },

]
</script>

<template>
   <div v-for="produto in produtos">
    <h3>{{ produto.nome }}</h3>
    <p>Categoria: {{ produto.categoria }}</p>
    <p>Preço: {{ produto.preco }}</p>
   </div>
</template>

