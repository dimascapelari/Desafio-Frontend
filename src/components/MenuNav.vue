<template>
  <div class="links">
    <a href="#">EMPRESA</a>
    <a href="#">CAMISARIA</a>
    <a href="#">ALFAIATARIA</a>
    <a href="#">DEPOIMENTOS</a>
    <a href="#">CONTATO</a>
  </div>
</template>

<script>
export default {
  name: "MenuNav",
};
</script>

<style>
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
</style>