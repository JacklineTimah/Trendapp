<script setup>
import TheNavbar from './components/TheNavbar.vue'; 
import HeroComponent from './components/HeroComponent.vue';
import TheCardComponents from './components/TheCardComponents.vue';
import SecttionTwoComponent from './components/SectionTwoComponent.vue';
import TheThirdCard from './components/TheThirdCard.vue';
import CompaniesCombo from './components/CompaniesCombo.vue';
import ForthCard from './components/ForthCard.vue';
import fifthSection from './components/fifthSection.vue';
import Getyourbest from './components/Getyourbest.vue';
import JoinUsSection from './components/JoinUsSection.vue';
import TheFooterSection from './components/TheFooterSection.vue';

</script>

<template>
  <div class="app">
    <TheNavbar />
    <HeroComponent />
    <TheCardComponents/>
    <SecttionTwoComponent />
    <TheThirdCard />
    <CompaniesCombo />
    <ForthCard />
    <fifthSection />
    <Getyourbest />
    <JoinUsSection />
    <TheFooterSection />
    
  </div>
</template>

<style scoped>
.app{
  background-color: black;
}

@media (min-width: 1024px){
  nav{
    padding: 0px 30px;
  }
}

@media (min-width: 1135px){
  nav{
    padding: 0px 80px;
  }
}

</style>
