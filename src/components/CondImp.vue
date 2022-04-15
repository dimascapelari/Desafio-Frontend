<template>
  <div class="condicao">
    <img class="img-condicao" src="../assets/weste.png" alt="" />

    <h1>CONDIÇÃO IMPERDÍVEL</h1>
    <h2>Compre hoje e garanta</h2>
    <p class="p1-condicao">
      - 12% de desconto e pagamento em até <strong>3x sem juros</strong>;
    </p>

    <p class="p2-condicao">
      - Até <strong>10 meses</strong> para confeccionar sua roupa. Não se<br />
      &nbsp; preocupe se suas medidas aumentaram ou diminuíram, estará sempre
      <br />&nbsp;&nbsp;elegante;
    </p>

    <p class="p3-condicao">
      - Condição muito especial por <strong>tempo limitado</strong>;
    </p>

    <p class="p4-condicao">
      - Poder presentear alguém com uma roupa de alta costura,
      <strong>exclusiva</strong>.
    </p>

    <button class="bt-condicao">Garanta essa condição especial!</button>
  </div>
</template>

<script>
export default {
  name: "CondImp",
};
</script>

<style>
.condicao {
  width: 1366px;
  height: 568px;
  background: #002432;
}

.condicao h1 {
  position: absolute;
  left: 5%;
  top: 1800px;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 400;
  font-size: 53px;
  line-height: 64px;
  text-transform: uppercase;
  color: #be9667;
}

.condicao h2 {
  position: absolute;
  left: 5%;
  top: 1900px;
  bottom: 60.83%;
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 400;
  font-size: 30px;
  line-height: 36px;
  color: #be9667;
}

.img-condicao {
  position: absolute;
  width: 330px;
  height: 500px;
  left: 860px;
  top: 1775px;
}

.condicao p {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 22px;
  line-height: 26px;
  color: #c4c4c4;
}

.p1-condicao {
  position: absolute;
  left: 5%;
  right: 30.05%;
  top: 1950px;
  bottom: 59.89%;
}

.p2-condicao {
  position: absolute;
  left: 5%;
  right: 40.26%;
  top: 2000px;
  bottom: 58.39%;
}

.p3-condicao {
  position: absolute;
  left: 5%;
  right: 30.05%;
  top: 2100px;
  bottom: 57.39%;
}

.p4-condicao {
  position: absolute;
  left: 5%;
  right: 34.92%;
  top: 2150px;
  bottom: 56.38%;
}

.bt-condicao {
  position: absolute;
  left: 5%;
  right: 0%;
  top: 2210px;
  bottom: 0%;
  width: 300px;
  height: 50px;
  font-family: "Lato";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 22px;
  text-align: center;
  color: #e5e5e5;
  border: none;
  background: #be9667;
  border-radius: 4px;
}

.bt-condicao:hover {
  background-color: #e0e0e0;
  text-decoration: none;
  transition: 0.8s;
  color: #002432;
}
</style>