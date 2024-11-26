<script setup>
import mapaImg from "@/assets/mapa.png";
</script>

<template>
  <div class="conteudo">
    <h1>Geografia</h1>
    <p>
      O Estado de Israel, em sua área total de 27 800 km², é descrito dentro das
      linhas de cessar-fogo e do autogoverno da Palestina. De forma alongada e
      estreita, tem em seu comprimento 470 km, e em sua largura máxima, 135 km.
      Suas fronteiras estão entre o Líbano, a Síria, a Jordânia, o Egito e o mar
      Mediterrâneo.
    </p>
    <div class="destaque">
      <div class="parag">
        <p>
          Dividido em quatro regiões geográficas — três faixas paralelas e uma
          grande área árida — tem em sua planície costeira do Mediterrâneo, os
          sítios mais férteis, que avançam em um total de quarenta quilômetros
          para o interior do país. A nordeste, nascem suas cadeias de montanhas,
          onde localiza-se ainda o planalto de Golan, formado por rochas de
          basalto, resultantes de erupções vulcânicas, que beiram o Vale do
          Hula. Seguindo a cadeia rochosa, localizam-se as montanhas da
          Galileia, compostas de rocha calcária branda e dolomita, que atingem
          até 1 200 m de altura.
        </p>
        <p>
          Acompanhando as cadeias montanhosas seguem córregos que mantém a
          região verde por todo o ano. Entre as montanhas da Galileia e da
          Samaria, encontra-se o Vale de Jizreel, dita a região mais agrícola de
          Israel. Seguindo a cadeia rochosa para o sul, vê-se o Negueve, que
          compõe quase a metade do território. Adiante, esta área torna-se mais
          árida, composta por planícies de arenito em cumes de pedras, crateras,
          platôs, montanhas ainda mais altas e três crateras erosivas, cuja
          maior mede 35 km de comprimento, de clima seco. Próximo a Eilat e ao
          mar Vermelho, a paisagem apresenta agudas elevações compostas por
          granito cinza e vermelho e arenito.
        </p>
      </div>
      <img :src="mapaImg" alt="mapa atual" />
    </div>
    <p class="ultimo">
      Ao oriente, percebe-se a fenda Sírio-Africana, divisora da crosta
      terrestre. Ao contrário do sul semiárido, o oriente é sua área
      setentrional e fértil, além de ser atravessada de norte a sul pelo rio
      Jordão, que possui um total de trezentos quilômetros. Este rio, nascido de
      neves do monte Hermon derretidas no verão, atravessa o vale do Hula, e o
      mar da Galileia, o maior reservatório de água potável do país situado
      entre as montanhas e o Planalto de Golan, e desemboca no mar Morto, o
      ponto mais baixo da superfície terrestre. Mesmo cheio durante a estação
      das chuvas, o rio Jordão é raso e estreito, com profundidade máxima de
      5,20 metros e largura máxima de 18,30 metros. Ao sul do mar Morto,
      encontra-se o Aravá,[153] chamada savana de Israel, que se estende até o
      golfo de clima sub-tropical e águas profundas, com recifes de corais e uma
      variada fauna marinha...
    </p>
  </div>
</template>

<style scoped>
h1 {
  font-size: 40px;
}

p {
  font-size: 20px;
  line-height: 1.2;
}

.destaque {
  display: flex;
  gap: 20px;
  margin-top: 20px;
}

.parag {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

img {
  width: 600px;
}

.ultimo {
  margin-top: 20px;
}

@media screen and (max-width: 767px) {
  .destaque {
    flex-direction: column;
  }

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
