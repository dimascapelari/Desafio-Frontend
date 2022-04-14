<template>
  <container>
    <header>
      <div class="imagem">
        <img src="./components/assets/Logo.png" alt="logomarca" />
      </div>
      <div class="links">
        <a href="#">EMPRESA</a>
        <a href="#">CAMISARIA</a>
        <a href="#">ALFAIATARIA</a>
        <a href="#">DEPOIMENTOS</a>
        <a href="#">CONTATO</a>
      </div>
    </header>

    <main>
      <div class="banner">
        <img src="./components/assets/Banner.png" alt="" />
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
      <img class="whatsapp" src="./components/assets/whatsapp.png" alt="" />
      <div class="renee">
        <div class="imagem-renee">
          <img src="./components/assets/crossed.png" alt="" />
          <h1 class="h1-renee">Renne Trajar</h1>
          <div class="risco-renee"></div>
          <p class="p1-renee">
            Com mais de 35 anos de experiência em camisas, calças e ternos sob
            medida, possuímos profissionais experientes e altamente
            qualificados. <br /><br />

            Cada cliente tem seu molde exclusivamente desenvolvido para seu
            biotipo através das medidas tiradas pelo próprio Sr. Renee, no
            escritório ou residência do cliente.
          </p>
          <p class="p2-renee">
            “Nosso objetivo é superar a expectativa do cliente
            proporcionando-lhe satisfação ao usar nossos produtos, aliado a um
            relacionamento franco e honesto, valorizando o ser humano.”
          </p>
          <p class="p3-renee">Renee Trajar</p>
          <img class="aspas" src="./components/assets/aspas.png" alt="" />
          <button class="bt-renee">Agende uma vizita!</button>
        </div>
      </div>

      <div class="nelson">
        <div class="imagem-background-nelson">
          <img src="./components/assets/tailor.png" alt="" />
        </div>
        <div class="imagem-nelson">
          <img
            class="img-nelson1"
            src="./components/assets/perfil.png"
            alt=""
          />
          <img
            class="img-nelson2"
            src="./components/assets/perfil1.png"
            alt=""
          />
          <div class="nelson-borda"></div>
          <p class="p1-nelson">
            “Faço roupas com o Renee Trajar há mais de duas décadas, o serviço é
            impecável em todos os detalhes, desde a costura ao caimento. O Renee
            tem uma equipe de mestre!”
          </p>
          <p class="p2-nelson">Nelson Garey</p>
          <p class="p3-nelson">Advogado | Nelson Advogados Associados</p>
        </div>
      </div>
      <div class="qualidade">
        <img class="icon0" src="./components/assets/icon0.png" />
        <p class="p01">QUALIDADE</p>
        <p class="p02">Camisaria e Alfaiataria 100% artesanal.</p>

        <img class="icon1" src="./components/assets/icon1.png" />
        <p class="p11">EXPERIÊNCIA</p>
        <p class="p12">
          Atendimento personalizado no escritório ou residência.
        </p>

        <img class="icon2" src="./components/assets/icon2.png" />
        <p class="p21">CONFIANÇA</p>
        <p class="p22">Tradição e modernidade proporcionando elegância.</p>
      </div>
      <div class="condicao">
        <img class="img-condicao" src="./components/assets/weste.png" alt="" />

        <h1>CONDIÇÃO IMPERDÍVEL</h1>
        <h2>Compre hoje e garanta</h2>
        <p class="p1-condicao">
          - 12% de desconto e pagamento em até <strong>3x sem juros</strong>;
        </p>

        <p class="p2-condicao">
          - Até <strong>10 meses</strong> para confeccionar sua roupa. Não se<br />
          &nbsp; preocupe se suas medidas aumentaram ou diminuíram, estará
          sempre <br />&nbsp;&nbsp;elegante;
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
      <div class="camisaria">
        <img
          class="img-camisaria"
          src="./components/assets/tailor1.png"
          alt=""
        />
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

      <div class="alfaiataria">
        <img
          class="img-alfaiataria"
          src="./components/assets/tailor2.png"
          alt=""
        />
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

      <div class="depoimentos">
        <img
          class="img-depoimentos"
          src="./components/assets/group.png"
          alt=""
        />
        <h1 class="h1-depoimentos">Depoimentos</h1>
        <img
          class="img-depo-redonda"
          src="./components/assets/persona4.png"
          alt=""
        />
        <div class="p-risco"></div>
        <p class="p-depoimentos">
          “Sou cliente do Renee há uns 12 anos. Nosso primeiro contato foi por
          intermédio de<br />
          meu pai, que já têm uma história de décadas com o querido Renee.<br />
          O excelente atendimento antes e pós venda e a alta qualidade dos
          materiais usados<br />
          colocam a Renee Trajar em um patamar acima dos demais do ramo.”
        </p>
        <p class="assinatura">William H. M. Garey</p>
        <p class="advogado">Advogado | Nelson Garey Advogados Associados</p>
        <img class="vetor-esq" src="./components/assets/VectorEsq.png" />
        <img class="vetor-dir" src="./components/assets/VectorDir.png" />
      </div>

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
      <div class="footer">
        <img class="logofooter" src="./components/assets/logofooter.png" />
        <p class="cnpj">CNPJ: 04.487.685/0001-01</p>
        <p class="copy">
          Copyright: 2021 © Renee Trajar - Todos os direitos reservados.
        </p>
        <img class="seta-topo" src="./components/assets/Vector.png" />
        <div class="retangulo-footer"></div>
      </div>
    </main>
  </container>
</template>

<script>
export default {};
</script>


<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,600;1,400&family=Lato:wght@300&family=Playfair+Display+SC&family=Playfair+Display:ital@1&family=Poppins:wght@300&display=swap");

header {
  display: flex;
  justify-content: space-between;
  width: 1366px;
  height: 90px;
  padding: 10px 30px;
  align-items: center;
  font-weight: 100;
  position: fixed;
  background: linear-gradient(180deg, #000000 29.73%, rgba(0, 0, 0, 0) 100%);
}

.banner {
  width: 1366px;
}

.links {
  padding-right: 30px;
}

.links a {
  margin-left: 40px;
  text-decoration: none;
  color: #949494;
  font-family: "Lato";
  font-style: normal;
  font-weight: 300;
  font-size: 16px;
  line-height: 19px;
  text-transform: uppercase;
}

.links a:hover {
  color: #014561;
  transition: 0.8s;
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

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>