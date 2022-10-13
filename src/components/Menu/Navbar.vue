<template>
<div className="flex place-items-center m-5">
    <h1 className="text-3xl mr-4">Controle Financeiro</h1>
    <ul className="flex">
        <ItemMenu :url="item" v-for="(item, index) in url" :key="index" className="mr-4 "/>
    </ul>
</div>
</template>
<script setup >
    import ItemMenu from './ItemMenu.vue'

    const url = [
        {url: 'home', nome: 'Home'}, 
        {url: 'listar', nome: 'Listar'},
        {url: 'cadastrar', nome: 'Cadastrar'},
        {url: 'Login', nome:'Login'}
        ] 
            

            
</script>