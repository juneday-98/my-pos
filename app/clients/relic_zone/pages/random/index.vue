<template>
    \ <div class="flex justify-center">
        <div class="w-96 round ring-1">
            <div class="m-3 flex justify-center">
                <img class="w-24" src="https://static.wikia.nocookie.net/houkai-star-rail/images/e/ee/Item_Champion%27s_Headgear.png" 
                
                />
            </div>
            <div class="p-3 m-3 text-left">
                <p>Name: {{'API'}}</p>
                <p>Level: {{'API'}}</p>
                <p>Rarity: {{'API'}}</p>
                <p>Section: {{'API'}}</p>
                <p>Main Stat: {{'API'}}</p>
                <p>Value: {{'API'}}</p>
            </div>
            <div class="p-3 m-3 flex justify-center">
                <button class="bg-black text-red-50 p-3">random</button>
            </div>
        </div>


    </div>
</template>
  
<script setup lang="ts">
const callRandomRelicApi = 'name';
</script>