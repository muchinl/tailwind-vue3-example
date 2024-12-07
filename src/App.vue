<script setup lang="ts">
import Card01 from './components/Card01.vue'
import Table01 from "./components/Table01.vue";
import ImageText01 from "./components/ImageText01.vue";
import ImageText02 from "./components/ImageText02.vue";
import Chat01 from "./components/Chat01.vue";
import PriceCard01 from "./components/PriceCard01.vue";
import Tab01 from "./components/Tab01.vue";
import FAQ02 from "./components/FAQ02.vue";
import Feature01 from "./components/Feature01.vue";
import Feature02 from "./components/Feature02.vue";
import Feature03 from "./components/Feature03.vue";
</script>

<template>
  <Card01/>
  <Table01/>
  <ImageText01 />
  <ImageText02 />
  <Chat01 />
  <PriceCard01/>
  <Tab01/>
  <Feature01 />
  <Feature02 />
  <Feature03 />
  <FAQ02 />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
