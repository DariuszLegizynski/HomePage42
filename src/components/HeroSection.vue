<template>
<section class="hero">
    <picture>
        <source media="(min-width:640px)" srcset="@/assets/pics/lesley-davidson-FYMY-DJPLGo-unsplash.jpeg">
        <img class="hero__img" src="@/assets/pics/mae-mu-YdN-kUtnOEQ-unsplash.jpeg" alt="lemon-hero" />
    </picture>
    
    <h2>I can be your hero babe</h2>
    <h5>I can kiss away your pain, oh yeah!</h5>
</section>
</template>

<script>
export default {

}
</script>

<style scoped>
.hero {
    margin-top: 4rem;
}

.hero__img {
    width: 100%;
    object-fit: contain;
}
</style>