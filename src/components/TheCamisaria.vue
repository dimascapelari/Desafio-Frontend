<template>
  <div class="camisaria">
    <img class="img-camisaria" src="../assets/tailor1.png" alt="" />
    <h1>CAMISARIA</h1>
    <p class="p1-camisaria">CONFECCIONADAS ARTESANALMENTE</p>
    <ul class="ul-1">
      <li>100% Algodão</li>
      <li>Monograma</li>
      <li>Slim</li>
    </ul>
    <ul class="ul-2">
      <li>Nacionais e Importados</li>
      <li>Tradicionais e Esportivos</li>
      <li>Casamentos</li>
    </ul>
    <h3></h3>
    <h4></h4>
    <button class="bt-camisaria">Quero um orçamento</button>
  </div>
</template>

<script>
export default {
  name: "TheCamisaria",
};
</script>

<style>
.camisaria {
  width: 1366px;
  height: 600px;
  background: white;
}

.camisaria h1 {
  position: absolute;
  left: 700px;
  top: 2450px;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 300;
  font-size: 62px;
  line-height: 75px;
  text-transform: uppercase;
  color: #014561;
}

.img-camisaria {
  position: absolute;
  left: 100px;
  top: 2370px;
  z-index: 1;
}

.camisaria h3 {
  position: absolute;
  width: 545px;
  height: 470px;
  border: 1px solid #1c86a4;
  box-sizing: border-box;
  left: 93px;
  top: 2378px;
  z-index: 2;
}

.camisaria h4 {
  position: absolute;
  width: 1015px;
  height: 385px;
  border: 1px solid #1c86a4;
  box-sizing: border-box;
  left: 220px;
  top: 2425px;
  z-index: 0;
}

.p1-camisaria {
  position: absolute;
  left: 730px;
  top: 2515px;
  font-family: "Lato";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 19px;
  text-transform: uppercase;
  color: #727272;
}

.ul-1 {
  position: absolute;
  left: 730px;
  top: 2600px;
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 400;
  font-size: 24px;
  line-height: 29px;
  color: #727272;
}

.ul-2 {
  position: absolute;
  left: 960px;
  top: 2600px;
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 400;
  font-size: 24px;
  line-height: 29px;
  color: #727272;
}

.bt-camisaria {
  width: 330px;
  height: 50px;
  background-color: #014561;
  color: #e5e5e5;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  text-align: center;
  position: absolute;
  left: 700px;
  top: 2710px;
  border: none;
  border-radius: 4px;
}

.bt-camisaria:hover {
  background-color: #0a022c;
  text-decoration: none;
  transition: 0.8s;
}
</style>