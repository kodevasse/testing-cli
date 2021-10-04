<template>
  <div class="hello">
    <h1>Hello World </h1>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body{
  font-size: 40px;
  text-align: center;
  padding-top: 100px;
}
</style>
