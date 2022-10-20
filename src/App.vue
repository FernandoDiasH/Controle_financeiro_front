<template>
<div className="grid grid-cols-8 grid-rows-6  gap-4 border border-black">
	<header className="col-span-8 ">
		<Navbar />
	</header>
	<div id="menuSide" className="grid-cols-2 col-start-3 col-end-8">

	</div>
	<main  className="row place-content-center border border-black grid-cols-6">
		<RouterView />
	</main>
	<footer className="col-span-8 ">
		
	</footer>
</div>
</template>
<script setup>
	import Navbar from './components/Menu/Navbar.vue'

</script>
