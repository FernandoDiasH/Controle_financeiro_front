<template>
    <div>
        <p v-for="value, index in values " :key="index">{{value}}</p> 
    </div>
</template>

<script setup>
    import {ref} from 'vue'

    let values = ref(['teste','teste','teste','teste','teste','teste','teste'])
</script>