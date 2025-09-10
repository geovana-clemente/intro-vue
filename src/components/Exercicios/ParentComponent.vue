<template>
  <div>
    <my-component>
      <template v-slot:header>
        <p>Este é o conteúdo do cabeçalho</p>
      </template>
      <template v-slot:body>
        <p>Este é o conteúdo do corpo</p>
      </template>
      <template v-slot:footer>
        <p>Este é o conteúdo do rodapé</p>
      </template>
    </my-component>
  </div>
</template>
