<template>
  <div class="alfaiataria">
    <img class="img-alfaiataria" src="../assets/tailor2.png" alt="" />
    <h1>ALFAIARIA</h1>
    <p class="p1-alfaiataria">TOTALMENTE FEITO A MÃO SOB MEDIDA</p>
    <ul class="ul-3">
      <li>Fio Super 120 e 130</li>
      <li>Lã fria Australiana</li>
      <li>Botões Importados</li>
    </ul>
    <ul class="ul-4">
      <li>Termos e Calças</li>
      <li>Paletós e Smokings</li>
      <li>Sociais e Esportivos</li>
    </ul>
    <h3></h3>
    <h4></h4>
    <button class="bt-alfaiataria">Quero um orçamento</button>
  </div>
</template>

<script>
export default {
  name: "TheAlfaiataria",
};
</script>

<style>
.alfaiataria {
  width: 1366px;
  height: 600px;
  background: white;
}

.img-alfaiataria {
  position: absolute;
  width: 547px;
  height: 488px;
  left: 688px;
  top: 2985px;
  z-index: 1;
}

.alfaiataria h3 {
  position: absolute;
  width: 565px;
  height: 470px;
  border: 1px solid #1c86a4;
  box-sizing: border-box;
  left: 678px;
  top: 2996px;
  z-index: 2;
}
.alfaiataria h4 {
  position: absolute;
  width: 1015px;
  height: 385px;
  border: 1px solid #1c86a4;
  box-sizing: border-box;
  left: 100px;
  top: 3045px;
  z-index: 0;
}

.alfaiataria h1 {
  position: absolute;
  left: 150px;
  top: 3070px;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 300;
  font-size: 62px;
  line-height: 75px;
  text-transform: uppercase;
  color: #014561;
}

.p1-alfaiataria {
  position: absolute;
  left: 163px;
  top: 3135px;
  font-family: "Lato";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 19px;
  text-transform: uppercase;
  color: #727272;
}

.ul-3 {
  position: absolute;
  left: 150px;
  top: 3220px;
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 400;
  font-size: 24px;
  line-height: 29px;
  color: #727272;
}

.ul-4 {
  position: absolute;
  left: 430px;
  top: 3220px;
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 400;
  font-size: 24px;
  line-height: 29px;
  color: #727272;
}

.bt-alfaiataria {
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
  left: 145px;
  top: 3340px;
  border: none;
  border-radius: 4px;
}

.bt-alfaiataria:hover {
  background-color: #0a022c;
  text-decoration: none;
  transition: 0.8s;
}
</style>