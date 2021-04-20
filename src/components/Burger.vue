<template>
	<div class="burger">
		<div
			class="burger__stick"
			:class="{ active: isBurgerActive }"
			@click.prevent="toggle"
		/>
	</div>
</template>

<script>
export default {
	data: () => ({
		isBurgerActive: false,
	}),
	methods: {
		toggle() {
			this.isBurgerActive = !this.isBurgerActive
		},
	},
}
</script>

<style scoped>
.burger {
	width: 3rem;
	height: 2rem;
	display: flex;
	position: relative;
	justify-content: center;
	align-items: center;
	cursor: pointer;
}

.burger__stick {
	width: 3rem;
	height: 0.25rem;
	background-color: orangered;
	border-radius: 10px;
	transition: all 0.5s ease-in-out;
}

.burger__stick::before,
.burger__stick::after {
	content: '';
	position: absolute;
	width: 3rem;
	height: 0.25rem;
	background-color: orangered;
	border-radius: 10px;
	transition: all 0.5s ease-in-out;
}

.burger__stick::before {
	transform: translateY(-12px);
}
.burger__stick::after {
	transform: translateY(12px);
}
.active {
	transform: translateX(-50px);
	background: transparent;
}
.active::before {
	transform: rotate(45deg) translate(35px, -35px);
}

.active::after {
	transform: rotate(-45deg) translate(35px, 35px);
}
</style>
