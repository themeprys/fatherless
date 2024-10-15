<template>
  <q-page>
    <HomeHero />
    <HomeTentang />
    <!-- <HomeProfil /> -->
    <HomeFitur />
    <HomeReinforcement />
  </q-page>
</template>

<script setup>
import HomeFitur from "src/components/home/homeFitur.vue";
import HomeHero from "src/components/home/homeHero.vue";
// import HomeProfil from "src/components/home/homeProfil.vue";
import HomeReinforcement from "src/components/home/homeReinforcement.vue";
import HomeTentang from "src/components/home/homeTentang.vue";

defineOptions({
  name: "BerandaPage",
});
</script>

