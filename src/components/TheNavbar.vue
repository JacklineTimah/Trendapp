<script setup>
import ButtonComponent from './ButtonComponent.vue';
</script>
<template>
    <div class="nav">
       <img src="@/assets/Logo.svg" alt="Fintrend logo">
       <p class="Trend">Findtrend</p>
       <ul class="links">
            <li>About</li>
            <li>How it work</li>
            <li>Pricing</li>
            <li>Solution</li>
            <li>Features</li>
       </ul>
        <div class="Log">
          <p>Login</p>
          <ButtonComponent class="button1" button-text="Register" />
          <img src="@/assets/iPhone 11 Pro/icon.svg" alt="humberger icon" class="humberger1"/>
        </div>
    </div>
</template>
<style scoped>
 /*.Trend{
    color: white;
    text-align: start;
    font-size: 24px;
    font-style: normal;
    font-weight: 700;
    line-height: 100%; 
 }*/
 .humberger1{
    display:none;
 }
 .nav{
    display: flex;
   /* gap: 183px;*/
    justify-content: space-between;
    background-color: black;
 }
 .links{
    display: flex;
    list-style-type: none;
    display: inline-flex;
    align-items: flex-start;
    gap: 40px;
    color: white;
 }
 .Log{
    display: flex;
    gap: 40px;
    color: white;
 }
 .button1{
display: inline-flex;
padding: 12px 32px;
justify-content: center;
align-items: center;
gap: 10px;
border-radius: 40px;
background: #FFF;
 }
 

@media (max-width:610px) {
.links{
display: none;
   }  
.Log{
display: none;
    }
.Trend{
display: none;
    }
.humberger1{
display: block;
flex-direction: row;
align-items: right;
   }
}

  

</style>