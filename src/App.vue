<template>
<div className="grid grid-cols-8 grid-rows-6 ">
	<header className="col-span-8 row-span-1 bg-red-200">
		<Navbar />
	</header>
	<div id="menuSide" className="col-span-2 row-span-4 bg-orange-200">
		<MenuLateral />
	</div>
	<main  className="col-span-6 row-span-4 bg-slate-300">
		<RouterView />
	</main>
	<footer className="col-span-8 row-span-1 m-10  bg-stone-500  ">
		<Footer />
	</footer>
</div>
</template>
<script setup>
	import Navbar from './components/Menu/Navbar.vue'
	import MenuLateral from './components/Menu/MenuLateral.vue'
	import Footer from './components/Footer/Footer.vue'
	

</script>
