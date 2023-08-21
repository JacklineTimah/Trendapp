<script setup>
import Sponsorsgrids from './sponsorsgrids.vue';
import microsoft from '../assets/microsoft.png'
import allianz from '../assets/Allianz.png'
import upwork from '../assets/upwork.png'
import verizon from '../assets/verizon.png'
import coinbase from '../assets/coinbase.png'
import expedia from '../assets/Expedia.png'
import airtable from '../assets/airtable.png'
import magento from '../assets/magento.png'
import carrera from '../assets/carrera.png'
import bonanza from '../assets/bonanza.png'
import suzuki from '../assets/suzuki.png'
import Grab from '@/assets/grab.png'
import Heineken from '@/assets/Heineken.png'
import algolia from '../assets/airtable.png'
import Wetransfer from '@/assets/Wetransfer.png'

</script>


<template>
  <div class="sponsoRS">
    <Sponsorsgrids class="sponsors" :sponsors="microsoft"/>
    <Sponsorsgrids class="sponsors" :sponsors="allianz"/>
    <Sponsorsgrids class="sponsors" :sponsors="upwork"/>
    <Sponsorsgrids class="sponsors" :sponsors="verizon"/>
    <Sponsorsgrids class="sponsors" :sponsors="airtable"/>
    <Sponsorsgrids class="sponsors" :sponsors="algolia"/>
    <Sponsorsgrids class="sponsors" :sponsors="carrera"/>
    <Sponsorsgrids class="sponsors" :sponsors="bonanza"/>
    <Sponsorsgrids class="sponsors" :sponsors="Grab"/>
    <Sponsorsgrids class="sponsors" :sponsors="magento"/>
    <Sponsorsgrids class="sponsors" :sponsors="suzuki"/>
    <Sponsorsgrids class="sponsors" :sponsors="expedia"/>
    <Sponsorsgrids class="sponsors" :sponsors="Heineken"/>
    <Sponsorsgrids class="sponsors" :sponsors="Wetransfer"/>
    <Sponsorsgrids class="sponsors" :sponsors="coinbase"/>
    <Sponsorsgrids class="sponsors" :sponsors="airtable"/>
  </div>
</template>


<style scoped>
/*.fourthCard{
  padding: 140px 140px 0px 140px;
  display: flex;
  flex-direction: column;
  column-gap: 80px;
  background-color: white;
}

.headOfcard4{
    display: flex;
    flex-direction: column;
    color: #000;
    text-align: center;
    font-size: 64px;
    font-style:normal;
    font-weight: 700;
    line-height: normal;
}*/

.sponsoRS{
  display: grid;
  padding: 40px 38px;
  grid-template-columns: 1fr 1fr 1fr 1fr;
  justify-content: space-evenly; 
  gap: 10px;
  border-radius: 8px;
  margin-top: 80px;
  text-align: center;
 justify-content: center;
 background-color: white;
 
}

.sponsors{
  align-items: center;
  text-align: center;
  align-content: center;
  padding: 24px 34px;
  display: flex;
  padding: 25px 0px;
 justify-content: center;
    align-items: center;
    width: 167px;
    display: flex;
    padding: 25px 0px;
    justify-content: center;
    align-items: center;
    width: 167px;
}

/* .brands{
 display: flex;
 flex-direction: column;
 justify-content: center;
} */


    /*display: flex;
    flex-wrap: wrap;
    width: 50%; 
    box-sizing: border-box;
    gap: 10px;*/
    
@media (min-width: 1024px){
 .main3 p{
    font-weight: 700;
    font-size: 64px;
    padding: 140px 140px 280px 140px;
 }
 .main3 h2{
    font-weight: 700;
    font-size: 64px;
    padding-bottom: 80px;
 }
 .sponsoRS{
    display: grid;
    grid-template-rows: repeat(4, 1fr);
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
    padding-bottom: 140px;
    margin: 0 auto;
   /*display: flex;
    flex-wrap: wrap; 
    box-sizing: border-box;
    align-items: center;
    justify-content: center;
    gap: 10px;*/
 }
 }


@media (min-width: 1125px){
    .sponsors{
        width: 266px;
    
    }
}

</style>