<template>
  <div class="bg">
    <Calculator/>
  </div>
</template>

<script>
import Calculator from './components/Calculator';
export default {
  components: {
    Calculator
  }
}
</script>

<style >
  .bg {
    padding: 2rem;
    background-color: gray;
    width: 100vw;
    height: 100vh;
  }
  html, body {
      font-family: 'Sora', sans-serif;
  }
</style>
