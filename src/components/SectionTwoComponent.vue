<script setup>

</script>

<template>
<div class="main1">
    <h2>Open new tabs is sh*t</h2>
    <img class="small" src="@/assets/finimage.png"/>
    <img class="big" src="@/assets/finibig.png"/>
    <p>A solution for your browser tabs and don’t make your device get slower over time. Get ease and faster to discover a trend with just one tab.</p>
</div>
</template>

<style scoped>
.big{
    display: none;
}

.main1{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 34px;
    background-color: #A8FF35;
}
.main1 h2{
    padding-top: 80px;
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 36px;
    font-style: normal;
    font-weight: 700;
    line-height: 112%;
}

.main1 p{
    color: #000;
    text-align: center;
    font-family: "Inter";
    font-size: 14px;
    font-style: normal;
    font-weight: 400;
    line-height: 150%;
    padding: 0px 44px 80px 45px;
}

@media (min-width: 1024px){
    .small{
        display: none;
    }
    .big{
        display: block;
    }
    .main1{
        gap: 60px;
    }
    .main1 h2{
        font-size: 72px;
    }
    .main1 p{
        font-size: 18px;
        padding: 0px 387px 140px 387px;
        align-items: center;
    }
}


</style>