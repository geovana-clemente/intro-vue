<script setup>
//import Exemplo01 from './components/Exemplo01Interpolacao.vue'
//import Exercicio1 from './components/Exercicios/Exercicio1.1.vue'
//import Exercicio2 from './components/Exercicios/Exercicio1.2.vue'
//import Exercicio3 from './components/Exercicios/Exercicio1.3.vue'
//import Exemplo02 from './components/Exemplo02condicional.vue'
//import Exercicio21 from './components/Exercicios/Exercicio2.1.vue'
//import Exercicio22 from './components/Exercicios/Exercicio2.2.vue'
//import Exemplo03 from './components/Exemplo03For.vue'
//import Exercicio31 from './components/Exercicios/Exercicio3.1.vue'
//import Exercicio32 from './components/Exercicios/Exercicio3.2.vue'
//import Exemplo04 from './components/Exemplo04HTML.vue'
//import Exercicio41 from './components/Exercicios/Exercicio4.1.vue'
//import Exemplo05 from './components/Exemplo05Model.vue'
//import Exercicio51 from './components/Exercicios/Exercicio5.1.vue' 
//import Exercicio52 from './components/Exercicios/Exercicio5.2.vue' 
//import Exemplo06 from './components/Exemplo06Classe.vue'
//import Exericio61 from './components/Exercicios/Exercicio6.1.vue'
//import Exemplo07 from './components/Exemplo07Clique.vue'
//import Exercicio71 from './components/Exercicios/Exercicio7.1.vue';
//import Exemplo08 from './components/Exemplo08Teclado.vue'
//import Exercicio81 from './components/Exercicios/Exercicio8.1.vue'
//import Exemplo09Enviar from './components/Exemplo09Enviar.vue';
//import Exemplo10Props from './components/Exemplo10Props.vue';

//const user = {
  //name: String, 
//  email: String, 
//  idade: Number,
  //telefone: String,
  //ativo: Boolean, 
//}

import Exercicio11ProductCard from './components/Exercicios/Exercicio1.1-ProductCard.vue';

</script>

<template>
  <Exemplo01></Exemplo01>
  <Exercicio1></Exercicio1>
  <Exercicio2></Exercicio2> 
  <Exercicio3></Exercicio3> 
  <Exemplo02></Exemplo02>
  <Exercicio21></Exercicio21> 
  <Exercicio22></Exercicio22>
  <Exemplo03></Exemplo03> 
  <Exercicio31></Exercicio31> 
  <Exercicio32></Exercicio32>
  <Exemplo04></Exemplo04> 
  <Exercicio41></Exercicio41>
  <Exemplo05></Exemplo05>
  <Exercicio51></Exercicio51>
  <Exercicio52></Exercicio52> 
  <Exemplo06></Exemplo06>
  <Exericio61></Exericio61>
  <Exemplo07></Exemplo07> 
  <Exercicio71></Exercicio71>
  <Exemplo08></Exemplo08>
  <Exercicio81></Exercicio81>
  <Exemplo09Enviar></Exemplo09Enviar>
  <!-- <Exemplo10Props 
    :name="user.name" 
    email="geovana@gmail.com"
    idade="17" 
    telefone="11999999999"
    :ativo="true" 
  ></Exemplo10Props> -->

  <Exercicio11ProductCard 
    title="Smartphone Samsung Galaxy S21" 
    :price="3999.99" 
    image="https://samsungbrshop.vtexassets.com/arquivos/ids/222466/image-147812a827ce414cbeecb5bb91eecb25-1-.jpg?v=638315272752900000" 
    :inStock="true"
  ></Exercicio11ProductCard>



</template>