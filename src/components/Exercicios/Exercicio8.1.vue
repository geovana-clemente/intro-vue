<script setup>
import {ref} from 'vue'
let inputValue = ref('')

function mensagem(){
    alert(`Executando a função: ${inputValue.value}`)
}

function mensagemKeydown(){
    alert(`Keydown: ${inputValue.value}`)
}

function mensagemKeypress(){
    alert(`Keypress: ${inputValue.value}`)
} 
</script>

<template>
    <input type="text" @keyup.enter="mensagem" v-model="inputValue"> 
    <input type ="text" @keydown.shift="mensagemKeydown" v-model="inputValue">
    <input type ="text" @keypress.d="mensagemKeypress" v-model="inputValue">

</template>