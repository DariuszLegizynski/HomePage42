<template>
  <div>
    <h2>Trusted us:</h2>
    <div class="companies">
      <div class="company">
        <h3>Company1</h3>
        <p>Awesome Experience</p>
      </div>
      <div class="company">
        <h3>Company2</h3>
        <p>Awesome Experience</p>
      </div>
      <div class="company">
        <h3>Company3</h3>
        <p>Awesome Experience</p>
      </div>
      <div class="company">
        <h3>Company4</h3>
        <p>Awesome Experience</p>
      </div>
      <div class="company">
        <h3>Company6</h3>
        <p>Awesome Experience</p>
      </div>
      <div class="company">
        <h3>Company6</h3>
        <p>Awesome Experience</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.companies {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  justify-content: center;
}
</style>
