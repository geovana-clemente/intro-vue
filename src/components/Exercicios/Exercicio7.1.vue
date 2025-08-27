<script setup>
import { ref } from 'vue'

const estado = ref('ativo')
</script>

<template>
  <div>
    <button @click="estado = 'ativo'">Ativo</button>
    <button @click="estado = 'inativo'">Inativo</button>
    <button @click="estado = 'carregando'">Carregando</button>
    <br><br>
    <button
      :class="estado === 'ativo' ? 'btn-ativo' : estado === 'inativo' ? 'btn-inativo' : 'btn-carregando'"
      :disabled="estado === 'carregando'"
    >
      {{ estado }}
    </button>
  </div>
</template>

<style scoped>
.btn-ativo {
  background: green;
  color: white;
}
.btn-inativo {
  background: red;
  color: white;
}
.btn-carregando {
  background: blue;
  color: white;
}

</style>