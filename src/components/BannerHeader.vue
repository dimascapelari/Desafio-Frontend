<template>
  <div>
    <div class="banner">
      <img src="../assets/Banner.png" alt="" />
    </div>

    <div class="texto-banner">
      <p class="p1">Elegante é ter um</p>
      <h1>ALFAIATE</h1>
      <p class="p2">para chamar de seu.</p>

      <p class="p3">
        COMPRE HOJE,
        <strong>
          EM ATÉ 3X<br />
          COM 12% DE DESCONTO</strong
        >
        E TENHA<br />
        10 MESES PARA CONFECCIONAR?
      </p>
      <button class="botao-orcamento">FAÇA JÁ UM ORÇAMENTO</button>
    </div>
    <img class="whatsapp" src="../assets/whatsapp.png" />
  </div>
</template>

<script>
export default {
  name: "BannerHeader",
};
</script>

<style>
.banner {
  width: 1366px;
}

.p1 {
  position: absolute;
  width: 348.69px;
  height: 43.05px;
  left: 5.98px;
  top: 12px;
}

.p2 {
  position: absolute;
  width: 289px;
  height: 43px;
  left: 124px;
  top: 130px;
}

.p3 {
  color: white;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 24px;
  line-height: 131%;

  position: absolute;
  width: 438px;
  height: 93px;
  left: 0px;
  top: 239px;
}

.botao-orcamento {
  position: absolute;
  left: 0%;
  right: 0%;
  top: 355px;
  bottom: 0%;
  width: 297px;
  height: 50px;
  background-color: #014561;
  border: none;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  text-align: center;
  color: #e5e5e5;
  border-radius: 4px;
}

.botao-orcamento:hover {
  background-color: #000000;
  text-decoration: none;
  border: solid 1px #be9667;
  transition: 0.8s;
}

.banner {
  display: flex;
  justify-content: center;
}

.banner img {
  width: 100%;
}

.texto-banner {
  color: white;
  position: absolute;
  font-size: 32px;
  left: 150px;
  top: 170px;
}

.p1,
.p2 {
  color: #be9667;
  font-family: "Playfair Display";
  font-style: italic;
  font-weight: 400;
  font-size: 32.5627px;
  line-height: 43px;
}

.texto-banner h1 {
  color: rgb(4, 55, 75);
  font-family: "Playfair Display SC";
  font-style: normal;
  font-weight: 400;
  font-size: 90.0346px;
  line-height: 120px;
  position: absolute;
  width: 404.18px;
  height: 119.58px;
  left: 0px;
  top: 33.52px;
}

.whatsapp {
  position: absolute;
  width: 67px;
  height: 67px;
  left: 1268px;
  top: 618px;
}
</style>