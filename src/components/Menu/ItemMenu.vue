<template>
    <li><a :href="url.url"> {{ url.nome  }}</a></li>

</template>

<script setup>
const props = defineProps({
    url:Object
})

</script>