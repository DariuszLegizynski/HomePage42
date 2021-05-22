<template>
  <section class="hero">
    <div class="hero__parallax">
      <div class="hero__parallax__layer hero__parallax__layer--back" />
      <div class="hero__parallax__layer hero__parallax__layer--base">
        <h2 class="hero__h2">I can be your hero babe</h2>
        <h5 class="hero__h5">I can kiss away your pain, oh yeah!</h5>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.hero {
  margin-top: 4rem;
}
.hero__parallax {
  height: 100vh;
  overflow-x: hidden;
  overflow-y: auto;
  perspective: 1px;
}
.hero__parallax__layer {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}
.hero__parallax__layer--back {
  transform: translateZ(-1px) scale(2);
  background-image: url('~@/assets/pics/mae-mu-YdN-kUtnOEQ-unsplash.jpeg');
  background-color: var(--color-main);
  background-size: cover;
  background-position: top;
}
.hero__parallax__layer--base {
  transform: translateZ(0);
}
.hero__h2 {
  position: absolute;
  top: 10rem;
  left: 2rem;
  padding-right: 2rem;
  color: var(--color-main);
}
.hero__h5 {
  position: absolute;
  top: 16.8rem;
  right: 2rem;
  padding-left: 8rem;

  color: var(--color-main-light);
}
</style>
