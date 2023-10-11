<template>
  <div>
    <HeaderSection />
    <IntroSection />
    <Degree />
    <Skills />
    <WorkExp />
    <LanguagePerk />
    <Portfolio />
  </div>
</template>

<script>
import HeaderSection from "./components/HeaderSection.vue";
import IntroSection from "./components/IntroSection.vue";
import Degree from "./components/Degree.vue";
import Skills from "./components/Skills.vue";
import WorkExp from "./components/WorkExp.vue";
import LanguagePerk from "./components/LanguagePerk.vue";
import Portfolio from "./components/Portfolio.vue";

export default {
  name: "App",
  components: {
    HeaderSection,
    IntroSection,
    Degree,
    Skills,
    WorkExp,
    LanguagePerk,
    Portfolio,
  },
};
</script>

<style>
* {
  font-family: Lato;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  font-size: 62.5%;
  background: #e9ecef;
}

.section {
  background: white;
  padding: 1.2rem 2rem;
  border-radius: 10px;
}
</style>
