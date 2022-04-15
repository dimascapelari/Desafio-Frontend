<template>
  <div class="renee">
    <div class="imagem-renee">
      <img src="../assets/crossed.png" alt="" />
      <h1 class="h1-renee">Renne Trajar</h1>
      <div class="risco-renee"></div>
      <p class="p1-renee">
        Com mais de 35 anos de experiência em camisas, calças e ternos sob
        medida, possuímos profissionais experientes e altamente qualificados.
        <br /><br />

        Cada cliente tem seu molde exclusivamente desenvolvido para seu biotipo
        através das medidas tiradas pelo próprio Sr. Renee, no escritório ou
        residência do cliente.
      </p>
      <p class="p2-renee">
        “Nosso objetivo é superar a expectativa do cliente proporcionando-lhe
        satisfação ao usar nossos produtos, aliado a um relacionamento franco e
        honesto, valorizando o ser humano.”
      </p>
      <p class="p3-renee">Renee Trajar</p>
      <img class="aspas" src="../assets/aspas.png" alt="" />
      <button class="bt-renee">Agende uma visita!</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "ReneeTrajar",
};
</script>

<style>
.renee {
  width: 100%;
  height: 550px;
  background: white;
}

.imagem-renee {
  position: absolute;
  width: 370px;
  height: 439px;
  left: 98px;
  top: 682px;
}

.h1-renee {
  position: absolute;
  height: 46px;
  left: 117.14%;
  right: -72%;
  top: -1px;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 300;
  font-size: 38px;
  line-height: 46px;
  display: flex;
  align-items: center;
  text-align: center;
  color: #014561;
}

.risco-renee {
  position: absolute;
  background-color: #70b0c4;
  width: 55px;
  height: 2px;
  top: 50px;
  left: 500px;
  z-index: 5;
}

.aspas {
  position: absolute;
  left: 1020px;
  top: 230px;
}

.p1-renee {
  position: absolute;
  width: 700px;
  height: 135px;
  left: 434px;
  top: 80px;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 19px;
  line-height: 141.3%;
  color: #333333;
}

.p2-renee {
  position: absolute;
  width: 700px;
  height: 102px;
  left: 434px;
  top: 250px;
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 400;
  font-size: 24px;
  line-height: 141.3%;
  color: #1c86a4;
}

.p3-renee {
  position: absolute;
  width: 151px;
  height: 28px;
  left: 1030px;
  top: 360px;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 500;
  font-size: 20px;
  line-height: 141.3%;
  color: #828282;
}

.bt-renee {
  position: absolute;
  left: 430px;
  right: 0%;
  top: 390px;
  bottom: 0%;
  background: #014561;
  border-radius: 2px;
  width: 300px;
  height: 50px;
  border-radius: 2px;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  text-align: center;
  color: #e5e5e5;
  border: none;
  border-radius: 4px;
}

.bt-renee:hover {
  background-color: #0a022c;
  text-decoration: none;
  transition: 0.8s;
}
</style>