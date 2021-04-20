<template>
	<header class="header">
		<img src="#" alt="logo" />
		<nav>
			<ul class="header__list">
				<li class="header__item"><a href="#">Home</a></li>
				<li class="header__item"><a href="#">About Us</a></li>
				<li class="header__item"><a href="#">CMS & Web</a></li>
				<li class="header__item"><a href="#">E-Commerce</a></li>
				<li class="header__item"><a href="#">Apps & Mobile</a></li>
				<li class="header__item"><a href="#">Full Service</a></li>
			</ul>
		</nav>
		<Burger />
	</header>
</template>

<script>
import Burger from './Burger'
export default {
	components: {
		Burger,
	},
}
</script>

<style scoped>
.header {
	display: flex;
	align-items: center;
	justify-content: space-around;
}
.header__list {
	display: flex;
}
.header__item {
	margin: 0 1rem;
}
</style>
