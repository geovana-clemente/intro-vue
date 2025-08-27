<script setup>
function validaFormulario(event){
    alert('Formulário enviado com sucesso!')
    event.preventDefault() // Previne o comportamento padrão do formulário 
}
</script>

<template>
    <form action="https://g1.globo.com" @submit="validaFormulario">
        <input type="submit" value="Enviar Formulário">
    </form> 
</template>