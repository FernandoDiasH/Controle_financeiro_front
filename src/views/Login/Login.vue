<template>
    <div className="w-screen h-screen grid grid-cols-1 grid-row-1 content-center place-items-center">
        <form  className=" w-[400px] h-[400px] bg-sky-300 grid content-center place-items-center rounded-3xl">
            <div className="flex flex-col justify-around h-[250px] w-[300px]  ">
                <Input name="E-mail"/>
                <Input name="Password"/>
            </div>
            <button type="submit" className="bg-blue-400 text-white font-mediun border-gray-500 w-28 h-9 rounded-lg mt-5 
            hover:bg-blue-700  active:border-gray-900 ">Login</button>
            <a href="/home">Home</a>
        </form>
    </div>
</template>

<script setup>
    import Input from '../../components/Inputs/Input.vue'

</script>