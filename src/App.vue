<template>
  <container>
    <TheHeder />

    <main>
      <BannerHeader />

      <ReneeTrajar />

      <NelsonGarey />

      <QualiExpConf />

      <CondImp />

      <TheCamisaria />

      <TheAlfaiataria />

      <TheDepoimentos />

      <TheForm />

      <TheFooter />
    </main>
  </container>
</template>

<script>
import BannerHeader from "./components/BannerHeader.vue";
import CondImp from "./components/CondImp.vue";
import NelsonGarey from "./components/NelsonGarey.vue";
import QualiExpConf from "./components/QualiExpConf.vue";
import ReneeTrajar from "./components/ReneeTrajar.vue";
import TheAlfaiataria from "./components/TheAlfaiataria.vue";
import TheCamisaria from "./components/TheCamisaria.vue";
import TheDepoimentos from "./components/TheDepoimentos.vue";
import TheFooter from "./components/TheFooter.vue";
import TheForm from "./components/TheForm.vue";
import TheHeder from "./components/TheHeder.vue";
export default {
  components: {
    TheHeder,
    BannerHeader,
    ReneeTrajar,
    NelsonGarey,
    QualiExpConf,
    CondImp,
    TheCamisaria,
    TheAlfaiataria,
    TheDepoimentos,
    TheForm,
    TheFooter,
  },
};
</script>


<style>
@import url("https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,600;1,400&family=Lato:wght@300&family=Playfair+Display+SC&family=Playfair+Display:ital@1&family=Poppins:wght@300&display=swap");
</style>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>