<template>
  <div class="contact" :class="{ open: showForm }">
    <button @click="showForm = !showForm" v-if="!showForm">contact</button>
    <div class="contact__container" v-if="showForm">
      <button class="contact__btn" @click="showForm = !showForm">x</button>
      <div class="contact__input">
        <h3>Hello there</h3>
        <p>Lorem Ipsum</p>
      </div>
      <form class="contact__form">
        <label class="contact__label" for="name">name</label>
        <input class="contact__input" name="name" type="text" required />
        <label class="contact__label" for="email">email</label>
        <input class="contact__input" name="email" type="email" required />
        <label class="contact__label" for="message">message</label>
        <textarea
          class="contact__input"
          name="message"
          type="text"
          placeholder="how should your website look like?"
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

<style scoped>
.contact {
  top: 5rem;
  right: 1rem;
  position: fixed;
  margin-left: 1rem;
  z-index: 100;
}
.open {
  background-color: var(--color-secondary);
  padding: 5rem 1rem;
  right: 0;
  margin-left: 0;
  top: 0rem;
}

.contact__container {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  overflow: scroll;
  position: relative;
  padding: 2rem 0rem 1rem 3rem;
  height: 100vh;
}

.contact__container button {
  position: absolute;
  top: 0rem;
  right: 0rem;
}

.contact__form {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
</style>
