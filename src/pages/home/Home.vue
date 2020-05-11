<template>
  <div class="home">
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
.home {
  background-image: url("../../assets/babymetal-bg.jpg");
  background-size: cover;
  background-position: center;
  height: 100vh;
}
</style>
