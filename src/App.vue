<template>
  <div>
    <input v-model='message'>
    <p>What you input: {{ message }}</p>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        message: "Hello World."
      }
    }
  }
</script>

<style>
  #app {
    font-size: 1.2rem;
    font-family: 'sans-serif';
  }
</style>

