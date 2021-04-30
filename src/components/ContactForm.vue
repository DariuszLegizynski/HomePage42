<template>
	<div class="contact">
		<button @click="showForm = !showForm" v-if="!showForm">
			contact
		</button>
		<div class="contact__container" v-if="showForm">
			<button class="contact__btn" @click="showForm = !showForm">
				x
			</button>
			<div class="contact__input">
				<h3>
					Hello there
				</h3>
				<p>Lorem Ipsum</p>
			</div>
			<form class="contact__form">
				<label class="contact__label" for="name">name</label>
				<input
					class="contact__input"
					name="name"
					type="text"
					required
				/>
				<label class="contact__label" for="email">email</label>
				<input
					class="contact__input"
					name="email"
					type="email"
					required
				/>
				<label class="contact__label" for="message">message</label>
				<textarea
					class="contact__input"
					name="name"
					type="text"
					placeholder="how should your website look like?"
					required
				/>
				<input class="contact__send" value="Send" type="submit" />
			</form>
			<div class="contact__success">
				<p>Thank you! We'll contact you soon.</p>
			</div>
			<div class="contact__failure">
				<p>Something went wrong, sorry.</p>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	data() {
		return {
			showForm: false,
		}
	},
}
</script>

<style>
.contact {
	margin-top: 5rem;
}
.contact__container {
	/* transform: translateX(100vh); */
}
</style>
