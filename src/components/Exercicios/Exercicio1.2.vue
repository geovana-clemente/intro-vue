<script setup>
let a = 15
let b = 25
</script> 

<template>
    <p>{{ `A soma de ${a} e ${b} é: ${a + b}` }}</p>
    <p>{{ `A subtração de ${a} e ${b} é: ${a - b}` }}</p>
    <p>{{ `A multiplicação de ${a} e ${b} é: ${a * b}` }}</p>
    <p>{{ `A divisão de ${a} e ${b} é: ${a / b}` }}</p> 
</template>