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

//  const user = {
//   name: String, 
//  email: String, 
// idade: Number,
// telefone: String,
// ativo: Boolean, 
// }

// import Exercicio11ProductCard from './components/Exercicios/Exercicio1.1-ProductCard.vue';

// import {ref} from 'vue'
// import Exemplo11Emits from './components/Exemplo11Emits.vue';
// const totalCliques = ref(0); 

// function atualizarTotalCliques(valor){
  // totalCliques.value = valor; 
// }


import Navbar from './components/Exercicios/Navbar.vue'
import NavItem from './components/Exercicios/NavItem.vue'
//import MyComponent from './components/Exercicios/MyComponent.vue';
//import ParentComponent from './components/Exercicios/ParentComponent.vue';


//import { ref } from 'vue'
//import Exercicio21CompradeProduto from './components/Exercicios/Exercicio2.1-CompradeProduto.vue'

//const produtos = ref([
    //{ nome: 'Batom Matte', price: 29.9 },
   // { nome: 'Blush em Pó', price: 59.9 },
   // { nome: 'Rímel Volume', price: 39.9 }
//])

//const mensagemCompra = ref('')

//function handleBuy(nomeProduto) {
  //  const msg = `Você comprou ${nomeProduto}`
   // mensagemCompra.value = msg
   // console.log(msg)
//}


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

  <!-- <Exercicio11ProductCard  --> 
    <!-- title="Smartphone Samsung Galaxy S21"  -->
    <!-- :price="3999.99"  -->
    <!-- image="https://samsungbrshop.vtexassets.com/arquivos/ids/222466/image-147812a827ce414cbeecb5bb91eecb25-1-.jpg?v=638315272752900000"  -->
    <!-- :inStock="true" -->
  <!-- ></Exercicio11ProductCard>  -->

  <!-- <Exemplo11Emits @update="atualizarTotalCliques"></Exemplo11Emits>  -->
    <!-- <P>Total de cliques: {{ totalCliques }}</P> --> 
<!-- <Exercicio21CompradeProduto> -->
   <!-- <h2>Produtos</h2> -->
    <!-- <div style="display: flex; gap: 1rem; flex-wrap: wrap;">
        <ProdutoCard
            v-for="(produto, i) in produtos"
            :key="produto.nome + i"
            :nome="produto.nome"
            :price="produto.price"
            @buy="handleBuy"
        />
    </div>
    <p v-if="mensagemCompra" style="font-weight: bold; color: #e0aaff; margin-top: 1rem;">{{ mensagemCompra }}</p>
</Exercicio21CompradeProduto>  -->
<ExercicioNavbar> </ExercicioNavbar>
  <Navbar>
    <NavItem>Home</NavItem>
    <NavItem>Sobre</NavItem>
    <NavItem>Contato</NavItem>
  </Navbar>











</template>