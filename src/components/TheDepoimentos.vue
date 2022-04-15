<template>
  <div class="depoimentos">
    <img class="img-depoimentos" src="../assets/group.png" alt="" />
    <h1 class="h1-depoimentos">Depoimentos</h1>
    <img class="img-depo-redonda" src="../assets/persona4.png" alt="" />
    <div class="p-risco"></div>
    <p class="p-depoimentos">
      “Sou cliente do Renee há uns 12 anos. Nosso primeiro contato foi por
      intermédio de<br />
      meu pai, que já têm uma história de décadas com o querido Renee.<br />
      O excelente atendimento antes e pós venda e a alta qualidade dos materiais
      usados<br />
      colocam a Renee Trajar em um patamar acima dos demais do ramo.”
    </p>
    <p class="assinatura">William H. M. Garey</p>
    <p class="advogado">Advogado | Nelson Garey Advogados Associados</p>
    <img class="vetor-esq" src="../assets/VectorEsq.png" />
    <img class="vetor-dir" src="../assets/VectorDir.png" />
  </div>
</template>

<script>
export default {
  name: "TheDepoimentos",
};
</script>

<style>
.img-depoimentos {
  width: 1366px;
}

.h1-depoimentos {
  position: absolute;
  height: 46px;
  left: 580px;
  top: 3600px;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 300;
  font-size: 38px;
  line-height: 46px;
  color: #f2f2f2;
}

.p-risco {
  position: absolute;
  background-color: #70b0c4;
  width: 55px;
  height: 2px;
  top: 3660px;
  left: 655px;
}

.img-depo-redonda {
  position: absolute;
  top: 3730px;
  left: 625px;
}

.p-depoimentos {
  position: absolute;
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 300;
  font-size: 26px;
  line-height: 31px;
  text-align: center;
  color: #c4c4c4;
  top: 3890px;
  left: 245px;
}

.assinatura {
  position: absolute;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  color: #be9667;
  top: 4030px;
  left: 600px;
}

.advogado {
  position: absolute;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 400;
  font-size: 20px;
  color: #c4c4c4;
  top: 4055px;
  left: 485px;
}

.vetor-esq {
  position: absolute;
  top: 3920px;
  left: 130px;
}

.vetor-dir {
  position: absolute;
  top: 3920px;
  left: 1200px;
}
</style>