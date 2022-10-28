<template>
    <table>
        <thead>
            <tr>
                <th v-for="chave in lancamentos[0]" :key="chave">{{chave }}</th>
            </tr>
        </thead>
        <tbody>
            <tr v-for="lancamento, chave in lancamentos" :key="chave">
                <td v-for="value, index in lancamento" :key="index">{{value}}</td>
            </tr>
        </tbody>
    </table>
</template>

<script setup>
    import { ref } from 'vue'
    
    let lancamentos= ref([
        {nome:"Fernando", Tipo:"saida", data:"20-10-2022"},
        {nome:"Amanda", Tipo:"Saida", data:"20-10-2022"},
        {nome:"Amanda", Tipo:"Saida", data:"20-10-2022"},
        ])
</script>