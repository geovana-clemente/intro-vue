<script setup>
let text = '<p>Olá, Vue!</p>'

</script>

<template>
  <strong>Exemplo 41</strong>

 
<p v-html="text"></p>
<p>{{ text }}</p>
  </template>
