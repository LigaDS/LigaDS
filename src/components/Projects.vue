<script setup>
import Card from './Card.vue'
import FootballTag from './tags/FootballTag.vue';
import IndustryTag from './tags/IndustryTag.vue';
import PandasTag from './tags/PandasTag.vue';
import PythonTag from './tags/PythonTag.vue';
</script>

<template>
  <div id="Projetos" class="projects-container d-flex flex-column justify-content-center align-items-center">
    <h1 class="fs-1 projects-header-title pb-4">Projetos Em Andamento</h1>
    <div class="card-wrapper d-flex flex-column justify-content-center align-items-center">
      
      <Card title="Nottingham Forest" description="O Nottingham Forest, um clube histórico do futebol inglês, busca consolidar-se na primeira divisão da Inglaterra após anos de dificuldade.">
        <p>Com um orçamento de 320 milhões, o objetivo é...</p>
          <ul>
            <li>Formar um elenco com raízes fortes, <mark>garantindo que oito dos jogadores sejam das ilhas britânicas</mark>, representando cada uma das nações: Inglaterra, Irlanda, Escócia, Irlanda do Norte e País de Gales.</li>
            <li>A <mark>média de idade</mark> do elenco precisa ser <mark>superior a 28 anos</mark>, trazendo a experiência necessária para evitar o rebaixamento.</li>
            <li>Além disso, para manter o equilíbrio financeiro, <mark>a diferença entre o jogador mais caro e o mais barato do time não deve ultrapassar 25 milhões.</mark></li>
          </ul>
          <div class="d-sm-flex py-3 gap-2">
            <FootballTag/>
            <PythonTag/>
            <PandasTag/>
        </div>
      </Card>

      <Card title="Juventus" description="A Juventus, a equipe mais vitoriosa da Itália, visa retornar ao topo do futebol europeu.">
      <p>Com um orçamento de 500 milhões para a temporada...</p>
      <ul>
        <li>A torcida demanda a <mark>contratação de um jogador estrela e estrangeiro</mark>, cujo valor seja <mark>pelo menos 20% superior ao segundo jogador mais caro</mark> do elenco.</li>
        <li>Além disso, o clube aposta em renovação, estipulando que a <mark>média de idade do time deve ser inferior a 26 anos</mark>, garantindo potencial de evolução.</li>
        <li>Outra restrição importante é <mark>evitar a presença de jogadores de nacionalidades rivais</mark>, como Brasil e Argentina ou Inglaterra e Alemanha, para assegurar harmonia no vestiário.</li>
      </ul>
      <div class="d-sm-flex py-3 gap-2">
          <FootballTag/>
          <PythonTag/>
          <PandasTag/>
      </div>
      </Card>

      <Card title="Athletic Bilbao" description="O Athletic Bilbao, um clube com forte tradição basca no futebol espanhol, busca renovar seu elenco respeitando suas raízes culturais e objetivos competitivos.">
        <p>Com um orçamento de 390 milhões...</p>
        <ul>
          <li>O time precisa <mark>montar uma equipe com 15 jogadores (incluindo dois goleiros)</mark>, sendo <mark>pelo menos quatro atletas de origem espanhola</mark> para preservar a identidade do clube. </li>
          <li>Além disso, o clube pretende garantir competitividade para se qualificar para competições europeias, exigindo que <mark>ao menos dois jogadores sejam ex-estrelas do futebol</mark>, trazendo experiência e impacto imediato.</li>
          <li>Por fim, <mark>uma jovem promessa (abaixo de 24 anos) deve fazer parte do elenco, estando entre os três jogadores de maior valor</mark>, preparando o clube para o futuro.</li>
        </ul>
        <div class="d-sm-flex py-3 gap-2">
          <FootballTag/>
          <PythonTag/>
          <PandasTag/>
        </div>
      </Card>

      <Card title="Planejamento e Controle de Produção" description="Uma indústria têxtil em Jacutinga, Minas Gerais, quer otimizar o dimensionamento de seus lotes, a fim de reduzir custos.">
        <p>A modelagem matemática do problema considera variáveis como a quantidade produzida, necessidade de produção, e estoque, além de restrições relacionadas à capacidade produtiva e demanda para...</p>
        <ul>
          <li><mark>Definir a quantidade ideal</mark> de cada peça de roupa a ser produzida <mark>mensalmente.</mark></li>
          <li>Garantir que a <mark>demanda seja atendida sem exceder a capacidade</mark> produtiva.</li>
          <li><mark>Minimizar os custos</mark> associados à produçao textil da fábrica.</li>
        </ul>

        <div class="d-sm-flex py-3 gap-2">
          <IndustryTag/>
          <PythonTag/>
          <PandasTag/>
        </div>
      </Card>

    </div>
  </div>
</template>

<style scoped>
mark {
  background-color: wheat;
}
.projects-container {
  padding: 8vh 4vw;
  text-align: center;
}

.card-wrapper {
  display: flex;
  flex-direction: column;
  width: 100%;
  max-width: 80vh;
  gap: 3vh;
}

.card {
  display: flex;
  flex-direction: row;
  align-items: center;
  text-align: left;
}

.icon {
  width: 2rem;
}
</style>
