<template>
<div className="grid grid-cols-8">
	<header className="col-span-8">
		<Navbar />
	</header>
	<div id="menuSide" className="col-span-2">
		<MenuLateral />
	</div>
	<main  className="col-span-6">
		<RouterView />
	</main>
	<footer className="col-span-8">
		
	</footer>
</div>
</template>
<script setup>
	import Navbar from './components/Menu/Navbar.vue'
	import MenuLateral from './components/Menu/MenuLateral.vue'
	

</script>
