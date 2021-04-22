<template>
  <div id="app">
    <Logo />
    <Hero />
  </div>
</template>

<script>
import Logo from "@/components/Header/Logo";
import Hero from "@/components/Header/Hero";

export default {
  name: 'App',
  components: {
    Logo,
    Hero
  }
}
</script>

<style lang="scss" scoped>
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>
