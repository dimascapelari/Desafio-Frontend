<template>
  <header>
    <div class="imagem">
      <img src="../assets/Logo.png" alt="logomarca" />
    </div>
    <MenuNav />
  </header>
</template>

<script>
import MenuNav from "./MenuNav.vue";
export default {
  components: { MenuNav },
  name: "TheHeder",
};
</script>

<style>
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
</style>