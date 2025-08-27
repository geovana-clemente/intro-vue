<script setup>
   let usuarioLogado = false
</script>


<template>
    <p v-if="usuarioLogado == true">Bem-vindo</p>
    <p v-else>Login</p>

</template>