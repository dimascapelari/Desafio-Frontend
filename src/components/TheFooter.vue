<template>
  <div class="footer">
    <img class="logofooter" src="../assets/logofooter.png" />
    <p class="cnpj">CNPJ: 04.487.685/0001-01</p>
    <p class="copy">
      Copyright: 2021 © Renee Trajar - Todos os direitos reservados.
    </p>
    <img class="seta-topo" src="../assets/Vector.png" />
    <div class="retangulo-footer"></div>
  </div>
</template>

<script>
export default {
  name: "TheFooter",
};
</script>

<style>
.linha-final {
  position: absolute;
  width: 1366px;
  height: 1px;
  left: 0px;
  top: 4670px;
  border: 1px solid #be9667;
}

.footer {
  width: 1366px;
  height: 160px;
  background: white;
}

.retangulo-footer {
  position: absolute;
  width: 40px;
  height: 40px;
  left: 1276px;
  top: 4744px;
  background: #ffffff;
  z-index: 0;
  border-radius: 4px;
  box-shadow: 5px 5px 5px #cccccc;
}

.retangulo-footer:hover {
  background-color: #036a96;
  text-decoration: none;
  transition: 0.8s;
}

.seta-topo {
  position: absolute;
  left: 1288px;
  top: 4759px;
  z-index: 1;
}

.logofooter {
  position: absolute;
  width: 138.6px;
  height: 68.45px;
  left: 198px;
  top: 4720px;
}

.cnpj {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 21px;
  color: #bdbdbd;
  position: absolute;
  height: 23px;
  left: 198px;
  top: 4790px;
}

.copy {
  font-family: "Poppins";
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 21px;
  text-align: center;
  color: #4f4f4f;
  position: absolute;
  width: 426px;
  height: 23px;
  left: 740px;
  top: 4790px;
}
</style>