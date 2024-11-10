<script setup>
    import {ref} from 'vue';
    const name = ref('');
</script>
<style>
    h2{
        word-wrap: break-word;
    }
</style>
<template>
    <h2> {{name}}</h2>
    
    <br>
    <input type="text" v-model="name">
</template>