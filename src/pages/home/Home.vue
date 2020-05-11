<template>
  <div class="home">
    <Icon />
    <a href="https://www.babymetal.com/en/">
      <figure>
        <img src="../../assets/babymetal-icon.png" alt="babymetal website" />
      </figure>
    </a>
    <Icon />
  </div>
</template>

<script>
import { Icon } from "../../components";
export default {
  name: "Home",
  components: {
    Icon
  }
};
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
