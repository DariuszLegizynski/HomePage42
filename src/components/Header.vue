<template>
	<header class="header">
		<img src="#" alt="logo" />
		<nav :class="{ active: isBurgerActive }">
			<ul class="header__list">
				<li class="header__item"><a href="#">Home</a></li>
				<li class="header__item"><a href="#">About Us</a></li>
				<li class="header__item"><a href="#">CMS & Web</a></li>
				<li class="header__item"><a href="#">E-Commerce</a></li>
				<li class="header__item"><a href="#">Apps & Mobile</a></li>
				<li class="header__item"><a href="#">Full Service</a></li>
			</ul>
		</nav>
		<Burger @click.prevent="toggle" :isBurgerActive="isBurgerActive" />
	</header>
</template>

<script>
import Burger from './Burger'
export default {
	data: () => ({
		isBurgerActive: false,
	}),
	components: {
		Burger,
	},
	methods: {
		toggle() {
			this.isBurgerActive = !this.isBurgerActive
		},
	},
}
</script>

<style scoped>
.header {
	display: flex;
	align-items: center;
	justify-content: space-around;
	position: fixed;
	top: 0;
	width: 100%;
	height: 4rem;
	z-index: 10;
	background-color: #fff;
	box-shadow: 0 5px 20px -10px #000;
}
.header__list {
	display: flex;
}
.header__item {
	margin: 0 1rem;
}
.active {
	display: block;
	visibility: visible;
}

@media only screen and (max-width: 800px) {
	nav {
		display: none;
		visibility: hidden;
	}
}
</style>
