<script setup>
import {ref} from 'vue'
    let count=ref(0); 
    function addvalue() {
        count.value++; 
        console.log(count)
    }


</script>

<template>
    <div @click="addvalue" v-on:click="" class="bg-purple-700 text-white py-2 px-4 rounded  inline-block hover:cursor-pointer transition-colors">
        ¡Presiona aquí! {{ count }}
    </div>
</template>