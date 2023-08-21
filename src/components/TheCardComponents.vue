<script setup>
    defineProps(["image", "CardText"]);
</script>

<template>
    <div class="Card">
        <img :src="image" />
        <p>{{ CardText }}</p>
        <img src="@/assets/Group 1.svg" />
        x
    </div>
</template>

<style scoped>
    .Card{
        display: flex;
        background-color: #181818;
        padding: 23px 20px;
        gap: 10px;
        align-items: center;
    }
    .Card p{
    color: #FFF;
    text-align: center;
    font-family: "Inter";
    font-size: 20.445px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    }
</style>