<script setup>
import { ref } from 'vue'
let nome = ref('') 
let email = ref('')
let idade= ref('')
let bio = ref('')
</script>

<template> 
    <p>Nome: {{ nome }}</p> 
    <input type="text" v-model="nome"> </input>
    <p>Email: {{ email }}</p>
    <input type="email" v-model="email"> </input>
    <p>Idade: {{ idade }}</p>
    <input type="number" v-model="idade"> </input>
    <p>Bio: {{ bio }}</p>
    <input type="text" v-model="bio"> </input> 
</template>