<script setup>
const props = defineProps({
    title: String, 
    price: Number, 
    image: String, 
    inStock: Boolean, 
})
</script>

<template>
    <div class="card" v-if="title">
        <h3>{{ title }}</h3>
        <p v-if="price">Preço do Produto: {{ price }}</p>
        <img v-if="image" :src="image" :alt="title" width="200"></img>
        <div :class="inStock ? 'inStock' : 'foraEstoque'">{{ inStock ? `Em Estoque` : `Fora de Estoque` }}</div>
    </div>
</template>

<style scoped>
.card{
    border: 1px solid #ccc;
    padding: 1rem;
    margin: 1rem;
} 
.inStock{
    color: green;
}
.foraEstoque{
    color: red;
} 
</style>