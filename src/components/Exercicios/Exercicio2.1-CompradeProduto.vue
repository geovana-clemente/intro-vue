<script setup>
const props = defineProps ({
    nome: String,
    price: Number
})

const emit = defineEmits(['buy'])

function comprar() {
    emit('buy', props.nome)
}
</script>

<template>
    <div class="produto-card">
        <h3>{{ nome }}</h3>
        <p>Preço: R$ {{ price.toFixed(2) }}</p>
        <button @click="comprar">Comprar</button>
    </div>
</template>
<style scoped>
.produto-card {
    border: 1px solid #ccc;
    color: black;
    padding: 1rem;
    border-radius: 8px;
    max-width: 250px;
    margin: 1rem auto;
    background: #f9f9f9;
}
button {
    background: #e0aaff;
    color: #333;
    border: none;
    border-radius: 4px;
    padding: 0.5rem 1rem;
    font-weight: bold;
    cursor: pointer;
    transition: background 0.2s;
}
button:hover {
    background: #c77dff;
}
</style>