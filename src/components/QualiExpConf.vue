<template>
  <div class="qualidade">
    <img class="icon0" src="../assets/icon0.png" />
    <p class="p01">QUALIDADE</p>
    <p class="p02">Camisaria e Alfaiataria 100% artesanal.</p>

    <img class="icon1" src="../assets/icon1.png" />
    <p class="p11">EXPERIÊNCIA</p>
    <p class="p12">Atendimento personalizado no escritório ou residência.</p>

    <img class="icon2" src="../assets/icon2.png" />
    <p class="p21">CONFIANÇA</p>
    <p class="p22">Tradição e modernidade proporcionando elegância.</p>
  </div>
</template>

<script>
export default {
  name: "QualiExpConf",
};
</script>

<style>
.qualidade {
  width: 1366px;
  height: 200px;
  background: white;
}

.icon0 {
  position: absolute;
  top: 1600px;
  left: 200px;
}

.p01 {
  position: absolute;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 29px;
  color: #1c86a4;
  left: 150px;
  top: 1640px;
}

.p02 {
  position: absolute;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 17px;
  left: 110px;
  top: 1670px;
  color: #727272;
}

.p11 {
  position: absolute;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 29px;
  color: #1c86a4;
  left: 600px;
  top: 1640px;
}

.p12 {
  position: absolute;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 17px;
  left: 520px;
  top: 1670px;
  color: #727272;
}

.p21 {
  position: absolute;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 600;
  font-size: 24px;
  line-height: 29px;
  color: #1c86a4;
  left: 1050px;
  top: 1640px;
}

.p22 {
  position: absolute;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 17px;
  left: 980px;
  top: 1670px;
  color: #727272;
}

.icon1 {
  position: absolute;
  top: 1600px;
  left: 650px;
}

.icon2 {
  position: absolute;
  top: 1600px;
  left: 1100px;
}
</style>