<template>
  <div id="app">
    <Cervejarias></Cervejarias>
  </div>
</template>

<script>
  import Cervejarias from './Cervejarias.vue'

  export default {
    components: {
      "Cervejarias": Cervejarias
    }
  }
</script>

<style>
  body {
    font-family: Helvetica, sans-serif;
  }
</style>