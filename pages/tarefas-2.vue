<template>
  <!-- <link href="../assets/css/main.css" rel="stylesheet"> -->
  <div class="container">
    <b-container>
    <menuHamburguer> </menuHamburguer>
    <div class="texto-fundo">
      <h3 class="titulo">Tarefas</h3>
      <img class="tabs" src="~/assets/Tabs.png" alt="Tabs icon" />
    </div>

    <div>
      <img class="plus" src="~/assets/Plus.png" alt="plus icon" />
      <p class="criar-lista">Criar Lista</p>
    </div>

   <div class="caixa-baixo">
    <div class="footer">
      <img class="metas" src="~/assets/emoji_events.png" alt="trofeu" />

      <img class="dns" src="~/assets/dns_2.png" alt="dns" />

      <img class="conteudos" src="~/assets/search.png" alt="lupa" />
    </div>
   
    <div class="footer-2">
      <p class="texto-metas">Metas</p>
      <p class="texto-dns">Tarefas</p>
      <p class="texto-conteudos">Conteúdos</p>

    </div>

          <div>
        <img class="ios-down" src="~/assets/iosDown.png" alt="Ios down" />
      </div> 
   </div>
  
     

    </b-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      titulo: 'Conteúdos',
      pessoas: [],
    }
  },
  methods: {
    digaOla() {
      alert('Bem vindo(a) Serotonina!')
    },
  },
}
</script>

