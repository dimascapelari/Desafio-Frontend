<template>
  <div class="form">
    <h1 class="h1-contato">Contato</h1>
    <div class="p-risco-form"></div>

    <input class="inp1" type="text" placeholder=" Nome" />
    <input class="inp2" type="text" placeholder=" E-mail" />
    <input class="inp3" type="text" placeholder=" Mensagem" />
    <button class="bt-inp-fim">Enviar Mensagem</button>
    <p class="telefone">TELEFONES</p>
    <p class="numero-telefone">+55(11)3088-0757</p>
    <p class="email">E-MAIL</p>
    <p class="endereco-email">renee@reneetrajar.com.br</p>
    <p class="atendimento">ATENDIMENTO PERSONALIZADO</p>
    <button class="bt-final">Clique aqui!</button>
    <div class="linha-final"></div>
  </div>
</template>

<script>
export default {
  name: "TheForm",
};
</script>

<style>
.form {
  width: 100%;
  height: 550px;
  background: white;
}

.h1-contato {
  position: absolute;
  height: 46px;
  left: 610px;
  top: 4150px;
  font-family: "Cormorant";
  font-style: normal;
  font-weight: 300;
  font-size: 38px;
  line-height: 46px;
  color: #1c86a4;
}

.p-risco-form {
  position: absolute;
  background-color: #70b0c4;
  width: 55px;
  height: 2px;
  top: 4210px;
  left: 645px;
}

.inp1 {
  position: absolute;
  top: 4260px;
  left: 635px;
  width: 600px;
  height: 42px;
}

.inp2 {
  position: absolute;
  top: 4320px;
  left: 635px;
  width: 600px;
  height: 42px;
}

.inp3 {
  position: absolute;
  top: 4380px;
  left: 635px;
  width: 600px;
  height: 77px;
}

.bt-inp-fim {
  position: absolute;
  width: 600px;
  height: 50px;
  background-color: #014561;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  text-align: center;
  color: #e5e5e5;
  top: 4480px;
  left: 635px;
  border: none;
  border-radius: 4px;
}

.bt-inp-fim:hover {
  background-color: white;
  border: solid 1px #014561;
  transition: 0.8s;
  color: #014561;
}

.telefone {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  text-transform: uppercase;
  color: #1c86a4;
  position: absolute;
  left: 198px;
  top: 4265px;
}

.numero-telefone {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 150.1%;
  color: #828282;
  position: absolute;
  left: 198px;
  top: 4295px;
}

.email {
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  text-transform: uppercase;
  color: #1c86a4;
  position: absolute;
  left: 198px;
  top: 4335px;
}

.endereco-email {
  position: absolute;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 19px;
  color: #828282;
  left: 198px;
  top: 4365px;
}

.atendimento {
  position: absolute;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  text-transform: uppercase;
  color: #1c86a4;
  left: 198px;
  top: 4440px;
}

.bt-final {
  position: absolute;
  width: 270px;
  height: 50px;
  left: 198px;
  top: 4480px;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 18px;
  line-height: 22px;
  text-align: center;
  color: #014561;
  background-color: white;
  border-radius: 4px;
  border: solid 1px #1c86a4;
}

.bt-final:hover {
  background-color: #014561;
  text-decoration: none;
  transition: 0.8s;
  color: white;
}
</style>