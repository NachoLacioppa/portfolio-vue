<template>
  <div class="titulo">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'titulo',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1{
    color: red;
  }
</style>
