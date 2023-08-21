<script setup>
import TheCardComponents from './TheCardComponents.vue';
import ButtonComponent from './ButtonComponent.vue'; 
import image1 from "@/assets/image 96.svg";
import image2 from "@/assets/image 97.svg";
import image3 from "@/assets/image 95.svg";
import image4 from "@/assets/Rectangle 6.svg";

</script>

<template>
    <section>
    <h2>Minimize your tabs.</h2>
    <h2>Find the trends!</h2>
    <p>Don’t let your computer memories consumes all of those browser tabs. 
        Findtrend  let you gathers all of your favorite website into one place.
    </p>

<div class="btn-text">
    <div>
    <ButtonComponent class="button" buttonText="Get Started 🔥"/>
    </div>
    <img class="btn-img" src="@/assets/img-hero.svg"/>
    </div>
    <div class="cards">
        <div>
        <div class="Crypto">
        <TheCardComponents class="card1" :image="image1" CardText="Cryptopunk - Search "/>
        </div>
        <div class="popular1">
        <TheCardComponents class="card2"  :image="image2" CardText="Popular Design - Search"/>
        </div>
        <div>
        <div class="product">
        <TheCardComponents class="card3"  :image="image3" CardText="Product Design - Search"/>
        </div>
        <div class="elon">
        <TheCardComponents class="card4"  :image="image4" CardText="Elon Musk - Search"/>
        </div>
        </div>
    </div>
    </div>
</section>
</template>

<style scoped>
  .btn-img{
    display: none;
  }
section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #000;
    padding-top: 56px;
    width: 100%;

   }

section h2{
    color: #FFF;
    text-align: center;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 900;
    line-height: 112%;
   }
section p{
    color: #8B8B8B;
    text-align: center;
    font-family: "Inter";
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
    padding: 16px 44px 32px 45px;
   }

   .button{
    background-color: #A8FF35;
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 14px;
    font-style: normal;
    font-weight: 700;
    line-height: 140%;
    align-items: center;
   }

   .cards{
padding: 50px 0px;
display: flex;
flex-direction: column;
align-items: center;

   }

.card1{   
transform: rotate(-4deg);

    
   }
   .card2{
    transform: rotate(2deg);
    
   }
   .card3{
    transform: rotate(-2deg);
   }
   .card4{
    transform: rotate(4deg);
   }


   @media (min-width: 1024px){
    .button{
        padding: 16px 32px;
    }
    .btn-img{
        display: block;
    }
    section h2{
        font-size: 72px;
    }
    section p{
        font-size: 18px; 
        padding: 24px 387px 40px 387px;
    }
    .btn-text{
        display: flex;
        gap: 5px;
    }
    .cards{
        flex-direction: row;
        padding: 100px 0px;
    }
   .card1, .card2, .card3, .card4{
    font-size: 23.806px;
   }
   .Crypto{
    padding-inline-start: 100px;
   }
   .popular1{
    padding-inline-end: 100px;
   }
   .product{
    padding-left: 150px;
   }
   .elon{
    padding-right: 100px;
   }
}
</style>