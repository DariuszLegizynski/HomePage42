<template>
  <div class="burger">
    <div class="burger__stick" :class="{ active: isBurgerActive }" />
  </div>
</template>

<script>
export default {
  props: {
    isBurgerActive: {
      type: Boolean,
      required: true,
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
  background-color: var(--color-main);
  border-radius: 10px;
  transition: all 0.5s ease-in-out;
}

.burger__stick::before,
.burger__stick::after {
  content: '';
  position: absolute;
  width: 3rem;
  height: 0.25rem;
  background-color: var(--color-main);
  border-radius: 10px;
  transition: all 0.5s ease-in-out;
}

.burger__stick::before {
  transform: translate(-24px, -12px);
}
.burger__stick::after {
  transform: translate(-24px, 12px);
}
.active {
  transform: translateX(-50px);
  background: transparent;
}
.active::before {
  transform: rotate(45deg) translate(18px, -18px);
}

.active::after {
  transform: rotate(-45deg) translate(18px, 18px);
}

@media only screen and (min-width: 640px) {
  .burger {
    display: none;
    visibility: hidden;
  }
}
</style>
