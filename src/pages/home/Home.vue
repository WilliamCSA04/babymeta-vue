<template>
  <div class="home">
    <div class="absolute">
      <ul class="list">
        <li>
          <Icon iconName="youtube" />
        </li>
        <li>
          <a href="https://www.babymetal.com/en/" class="icon-size">
            <figure>
              <img
                src="../../assets/babymetal-icon.png"
                alt="babymetal website"
              />
            </figure>
          </a>
        </li>
        <li>
          <Icon iconName="spotify" />
        </li>
      </ul>
    </div>
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
  background-position: bottom;
  height: 100vh;
  width: 100%;
  position: relative;
}
.icon-size {
  display: block;
  width: 6em;
  height: 6em;
}
.icon-size > figure {
  width: 6em;
  height: 6em;
}
.icon-size > figure > img {
  width: 6em;
  height: 6em;
}
.absolute {
  position: absolute;
  width: 100%;
  bottom: 0;
}
.list {
  list-style: none;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  align-items: center;
}
</style>
