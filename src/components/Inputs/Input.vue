<template>
    <div className="">
        <label :for="name" className="">{{name}}</label>
        <input :name="name" >
    </div>
</template>

<script setup>
    defineProps({
        name:String
    })

</script>