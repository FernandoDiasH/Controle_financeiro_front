<template>
    <div className="ml-5">
        <ul>
            <li v-for="content, index in links" :key="index"><a :href="content.url">{{content.label}}</a></li>
        </ul>
    </div>
</template>

<script setup>
    import {ref} from 'vue'
    const links = ref([
        {url: '#', label:'Teste'},
        {url: '#', label:'Teste'},
        {url: '#', label:'Teste'},
        {url: '#', label:'Teste'},
        {url: '#', label:'Teste'},
        {url: '#', label:'Teste'},
    ])

</script>