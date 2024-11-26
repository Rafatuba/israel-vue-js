<script setup>
import { ref } from "vue";
import bannerIsrael from "@/assets/banner-israel.png";
</script>

<template>
  <div class="img">
    <img :src="bannerIsrael" alt="banner Israel" />
  </div>
  <h1>Israel</h1>
  <p>
    Israel (em hebraico: יִשְׂרָאֵל, Yisra'el; em árabe: إِسْرَائِيلُ, Isrā'īl),
    oficialmente Estado de Israel (em hebraico: מדינת ישראל), é uma democracia
    parlamentar localizada no Oriente Médio, ao longo da costa oriental do mar
    Mediterrâneo. O país faz fronteira com o Líbano ao norte, com a Síria a
    nordeste, com a Jordânia e a Cisjordânia a leste, com o Egito e a Faixa de
    Gaza ao sudoeste, e com o golfo de Acaba, no mar Vermelho, ao sul.
    Geograficamente, contém diversas características dentro de seu território
    relativamente pequeno. Israel é definido como um "Estado Judeu e
    Democrático" em suas Leis Básicas e é o único Estado de maioria judia do
    mundo.
  </p>
  <br />
  <p>
    Após a adoção de uma resolução pela Assembleia Geral das Nações Unidas em 29
    de novembro de 1947, recomendando a adesão e implementação do Plano de
    Partilha da Palestina para substituir o Mandato Britânico, em 14 de maio de
    1948, David Ben-Gurion, o chefe-executivo da Organização Sionista Mundial e
    presidente da Agência Judaica para a Palestina, declarou o estabelecimento
    de um Estado Judeu em Eretz Israel, a ser conhecido como o Estado de Israel,
    uma entidade independente do controle britânico. As nações árabes vizinhas
    invadiram o recém-criado país no dia seguinte, em apoio aos árabes
    palestinos. Israel, desde então, travou várias guerras com os Estados árabes
    circundantes, no decurso das quais ocupou os territórios da Cisjordânia,
    península do Sinai, Faixa de Gaza e colinas de Golã. Partes dessas áreas
    ocupadas, incluindo Jerusalém Oriental, foram anexadas por Israel, mas a
    fronteira com a vizinha Cisjordânia ainda não foi definida de forma
    permanente. Israel assinou tratados de paz com Egito e Jordânia, porém os
    esforços para solucionar o conflito israelo-palestino até agora não
    resultaram em paz...
  </p>
</template>

<style scoped>
.img {
  width: 100%;
}
img {
  width: 100%;
}

h1 {
  font-size: 40px;
}

p {
  font-size: 20px;
  line-height: 1.2;
}

@media screen and (max-width: 767px) {
  img {
    width: 100%;
  }

  h1 {
    font-size: 34px;
  }

  p {
    font-size: 18px;
  }
}
</style>
