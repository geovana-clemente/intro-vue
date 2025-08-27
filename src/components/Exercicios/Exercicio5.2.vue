<script setup>
import { ref } from 'vue'
let peso = ref('') 
let altura = ref('')
</script> 

<template> 
    <p>Peso: {{ peso }}</p> 
    <input type="number" v-model="peso"> </input>
    <p>Altura: {{ altura }}</p>
    <input type="number" v-model="altura"> </input> 
    <p>IMC: {{ (peso / (altura * altura)).toFixed(2) }}</p>
    <p v-if="(peso / (altura * altura)) < 18.5">Abaixo do peso</p>
    <p v-else-if="(peso / (altura * altura)) < 25">Peso normal</p>
    <p v-else-if="(peso / (altura * altura)) < 30">Sobre Peso</p> 
    <p v-else-if="(peso / (altura * altura)) > 30">Obesidade</p> 
   
</template>