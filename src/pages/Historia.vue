<script setup>
import HistoriaImg from "@/assets/historia.png";
</script>

<template>
  <div class="conteudo">
    <img :src="HistoriaImg" alt="banner historia" />
    <div class="textos">
      <h1>História</h1>
      <p>
        A história da Antiga Israel abrange o período desde o século XX a.C. até
        à expulsão e Diáspora do povo judaico no século I, na área compreendida
        entre o mar Mediterrâneo, o deserto do Sinai, as montanhas do Líbano e o
        deserto da Judeia. Concentra-se especialmente no estudo do povo judeu
        neste período, e de forma secundária dos outros povos que com ele
        conviveram, como os filisteus, fenícios, moabitas, idumeus, hititas,
        madianitas, amoritas e amonitas. As fontes sobre este período são
        principalmente a escrita clássica como a Bíblia hebraica ou Tanakh
        (conhecida pelos cristãos como Antigo Testamento), o Talmude, o livro
        etíope Kebra Nagast e escritos de Nicolau de Damasco, Artapano de
        Alexandria, Fílon e Josefo. Outra fonte principal de informação são os
        achados arqueológicos no Egito, Moabe, Assíria ou Babilónia, e os
        vestígios e inscrições no próprio território.
      </p>
    </div>
  </div>
  <p class="text-botton">
    A Terra de Israel, conhecida em hebraico como Eretz Israel, é sagrada para o
    povo judeu desde os tempos bíblicos. De acordo com a Torá, a Terra de Israel
    foi prometida aos três patriarcas do povo judeu, por Deus, como a sua
    pátria; estudiosos têm colocado este período no início do 2º milênio a.C.. A
    terra de Israel guarda um lugar especial nas obrigações religiosas judaicas,
    englobando os mais importantes locais do judaísmo (como os restos do
    Primeiro e Segundo Templos do povo judeu). A partir do século X a.C. uma
    série de reinos e estados judaicos estabeleceram um controle intermitente
    sobre a região que durou cerca de 150 anos, para o Reino de Israel, até à
    sua conquista pelos assírios em 721 a.C., e quatro séculos para o Reino de
    Judá, até à sua conquista por Nabucodonosor II em 586 a.C. e destruição do
    Templo de Salomão pelos babilónios. Em 140 a.C. a revolta dos Macabeus levou
    ao estabelecimento do Reino Hasmoneu de Israel, cuja existência enquanto
    reino independente durou 77 anos, até à conquista de Jerusalém por Pompeu em
    63 a.C., altura em que se tornou um reino tributário do Império Romano...
  </p>
</template>

<style scoped>
.conteudo {
  display: flex;
  gap: 20px;
}

img {
  width: 600px;
}

h1 {
  font-size: 40px;
}

p {
  font-size: 20px;
  line-height: 1.2;
}
.text-botton {
  margin-top: 20px;
}

@media screen and (max-width: 767px) {
  .conteudo {
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
