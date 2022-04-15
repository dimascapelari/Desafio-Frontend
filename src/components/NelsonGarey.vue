<template>
  <div class="nelson">
    <div class="imagem-background-nelson">
      <img src="../assets/tailor.png" alt="" />
    </div>
    <div class="imagem-nelson">
      <img class="img-nelson1" src="../assets/perfil.png" alt="" />
      <img class="img-nelson2" src="../assets/perfil1.png" alt="" />
      <div class="nelson-borda"></div>
      <p class="p1-nelson">
        “Faço roupas com o Renee Trajar há mais de duas décadas, o serviço é
        impecável em todos os detalhes, desde a costura ao caimento. O Renee tem
        uma equipe de mestre!”
      </p>
      <p class="p2-nelson">Nelson Garey</p>
      <p class="p3-nelson">Advogado | Nelson Advogados Associados</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "NelsonGarey",
};
</script>

<style>
.nelson {
  width: 1366px;
  height: 360px;
  background: #eff7f9;
}

.img-nelson1 {
  position: absolute;
  width: 313px;
  height: 360px;
  left: 1053px;
  top: 1178px;
  opacity: 1;
  transition: 400ms;
}

.img-nelson1:hover {
  opacity: 0.3;
}

.img-nelson2 {
  position: absolute;
  width: 300px;
  height: 370px;
  left: 820px;
  top: 1180px;
}

.nelson-borda {
  position: absolute;
  width: 220.95px;
  height: 318.24px;
  left: 860px;
  top: 1205px;
  border: 8px solid #ffffff;
  box-sizing: border-box;
  transform: rotate(7.42deg);
}

.p1-nelson {
  position: absolute;
  width: 630px;
  height: 102px;
  left: 168px;
  top: 1268px;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 24px;
  line-height: 141.3%;
  text-align: center;
  color: #828282;
}

.p2-nelson {
  position: absolute;

  height: 40px;
  left: 415px;
  top: 1417px;
  font-family: "Cormorant";
  font-style: italic;
  font-weight: 400;
  font-size: 28px;
  line-height: 141.3%;
  text-align: center;
  color: #014561;
}

.p3-nelson {
  position: absolute;
  width: 421px;
  height: 28px;
  left: 272px;
  top: 1455px;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 20px;
  line-height: 141.3%;
  text-align: center;
  color: #be9667;
}

.imagem-background-nelson img {
  position: absolute;
  width: 905px;
  height: 360px;
  left: 148px;
  top: 1178px;
}
</style>