<template>
    <div className="flex flex-col ">
        <label :for="name" className="mb-4">{{name}}</label>
        <input 
        :name="name" 
        className="border border-gray-300 h-10 rounded-lg py-2 px-3 
        focus:outline-none focus:border-blue-600 focus:ring-blue-600" >
    </div>
</template>

<script setup>
    defineProps({
        name:String
    })

</script>