<template>
  <section class="hero">
    <ScrollParallax class="hero__leaf1" direction="y" :speed="-0.1">
      <img src="~@/assets/pics/leaves/leaf1.png" alt="leaf1" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf2" direction="y" :speed="-0.05">
      <img src="~@/assets/pics/leaves/leaf2.png" alt="leaf2" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf3" direction="y" :speed="-0.2">
      <img src="~@/assets/pics/leaves/leaf3.png" alt="leaf3" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf4" direction="y" :speed="-0.75">
      <img src="~@/assets/pics/leaves/leaf4.png" alt="leaf4" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf5" direction="y" :speed="-0.5">
      <img src="~@/assets/pics/leaves/leaf5.png" alt="leaf5" c />
    </ScrollParallax>

    <ScrollParallax class="hero__leaf6" direction="y" :speed="-1.5">
      <img src="~@/assets/pics/leaves/leaf6.png" alt="leaf6" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf7" direction="y" :speed="-1">
      <img src="~@/assets/pics/leaves/leaf7.png" alt="leaf7" />
    </ScrollParallax>
    <ScrollParallax class="hero__title" direction="y" :speed="-2">
      <h2 class="hero__h2">We are the ANSWER</h2>
    </ScrollParallax>
  </section>
</template>

<script>
import ScrollParallax from 'vue3-parallax/src/components/ScrollParallax.vue'

export default {
  components: {
    ScrollParallax
  }
}
</script>

<style scoped>
.hero {
  background: url(~@/assets/pics/lesley-davidson-FYMY-DJPLGo-unsplash.jpeg)
    no-repeat center center/cover fixed;
  height: 100vh;
  position: relative;
}
.hero img {
  height: 4rem;
}
.hero div {
  position: absolute;
}
.hero__leaf1 {
  top: 14rem;
  left: 16rem;
}
.hero__leaf2 {
  top: 18rem;
  left: 4rem;
}
.hero__leaf3 {
  top: 21rem;
  right: 18rem;
}
.hero__leaf4 {
  top: 11rem;
  right: 2rem;
}
.hero__leaf5 {
  bottom: 13rem;
  left: 14rem;
}
.hero__leaf6 {
  bottom: 9rem;
  left: 7rem;
}
.hero__leaf7 {
  bottom: 4rem;
  right: 2rem;
}
.hero__title {
  bottom: 1rem;
  left: 50%;
}
</style>
