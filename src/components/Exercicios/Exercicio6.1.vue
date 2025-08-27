<script setup>
import { ref } from 'vue'

const estado = ref('ativo') // 'ativo', 'inativo', 'carregando'

function setEstado(novoEstado) {
  estado.value = novoEstado
}
</script>

<template>
  <div>
    <button
      :class="{ ativo: estado === 'ativo' }"
      @click="setEstado('ativo')"
    >
      Ativo
    </button>
    <button
      :class="{ inativo: estado === 'inativo' }"
      @click="setEstado('inativo')"
    >
      Inativo
    </button>
    <button
      :class="{ carregando: estado === 'carregando' }"
      @click="setEstado('carregando')"
    >
      Carregando
    </button>
  </div>

  <p>
    Estado atual:
    <span :class="estado">{{ estado }}</span>
  </p>
</template>

<style scoped>
.ativo {
  background: green;
  color: white;
}
.inativo {
  background: gray;
  color: white;
}
.carregando {
  background: orange;
  color: white;
}
</style>