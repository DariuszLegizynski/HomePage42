<template>
  <section class="hero">
    <ScrollParallax class="hero__leaf1" direction="y" :speed="0.8">
      <img src="~@/assets/pics/leaves/leaf1.png" alt="leaf1" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf2" direction="y" :speed="0.7">
      <img src="~@/assets/pics/leaves/leaf2.png" alt="leaf2" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf3" direction="y" :speed="0.6">
      <img src="~@/assets/pics/leaves/leaf3.png" alt="leaf3" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf4" direction="y" :speed="0.3">
      <img src="~@/assets/pics/leaves/leaf4.png" alt="leaf4" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf5" direction="y" :speed="0.5">
      <img src="~@/assets/pics/leaves/leaf6.png" alt="leaf6" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf6" direction="y" :speed="0.1">
      <h2 class="hero__h2">We are the ANSWER</h2>
    </ScrollParallax>
    <ScrollParallax class="hero__leaf7" direction="y" :speed="0.3">
      <img src="~@/assets/pics/leaves/leaf7.png" alt="leaf7" />
    </ScrollParallax>
    <ScrollParallax class="hero__leaf8" direction="y" :speed="0.01">
      <img src="~@/assets/pics/leaves/leaf5.png" alt="leaf5" c />
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
  background: url(~@/assets/pics/mae-mu-YdN-kUtnOEQ-unsplash.jpeg) no-repeat
    center center/cover fixed;
  height: 100vh;
}
.hero img {
  height: 4rem;
}
</style>
