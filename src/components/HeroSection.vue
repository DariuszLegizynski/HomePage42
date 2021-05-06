<template>
<section class="hero">
    <picture>
        <source media="(min-width:640px)" srcset="@/assets/pics/lesley-davidson-FYMY-DJPLGo-unsplash.jpeg">
        <img class="hero__img" src="@/assets/pics/mae-mu-YdN-kUtnOEQ-unsplash.jpeg" alt="lemon-hero" />
    </picture>
    
    <h2 class="hero__h2">I can be your hero babe</h2>
    <h5 class="hero__h5">I can kiss away your pain, oh yeah!</h5>
</section>
</template>

<script>
export default {

}
</script>

<style scoped>
.hero {
    margin-top: 4rem;
    position: relative;
}

.hero__img {
    width: 100%;
    object-fit: contain;
}

.hero__h2{
    position: absolute;
    top: 1rem;
    left: 2rem;
    padding-right: 2rem;
  color: white;
  z-index: 1;
}

.hero__h5{
    position: absolute;
    top: 6.8rem;
    right: 2rem;
    padding-left: 8rem;

  color: white;
  z-index: 1;
}
</style>