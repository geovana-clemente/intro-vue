<script setup>
   let idade = 20
   
</script>


<template>
    <p v-if="idade <= 12 ">Criança</p>
    <p v-else-if="idade <=17">Adolescente</p>
    <p v-else-if="idade >= 60">Idoso</p> 
    <p v-else-if="idade <= 59">Adulto</p>

</template>