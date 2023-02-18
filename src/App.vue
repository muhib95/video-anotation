<template>
  <Header />
  <Hero />
  <Company />
  <Principles />
  <Footer />
</template>

<script>
import Header from "./components/Header/HeaderHead";
import Footer from "./components/Footer/FooterFoot";
import Hero from "./components/Heros/HeroTop.vue";
import Company from "./components/Company/CompanyBrand.vue";
import Principles from "./components/Principles/PrinciplesSupervisely.vue";
export default {
  name: "App",
  components: {
    Header,
    Footer,
    Hero,
    Company,
    Principles,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
