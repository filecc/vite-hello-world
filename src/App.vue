<template>
  <div>
    <AppTitle />
    <AppHero />
  </div>
</template>

<script>
  import AppTitle from './components/AppTitle.vue';
  import AppHero from './components/AppHero.vue';
  export default {
    components: {
      AppTitle,
      AppHero,
    }
  }
</script>

<style lang="css" scoped>
  div{
    font-family: sans-serif;
  }
</style>