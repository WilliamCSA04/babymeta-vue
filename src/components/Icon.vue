<template>
  <a
    href="https://www.youtube.com/channel/UC33_tIj4m1_XaqfFcomShvw"
    class="icon-link"
  >
    <font-awesome-icon :icon="['fab', iconName]" size="4x" />
  </a>
</template>

<style scoped>
.icon-link {
  width: 9em;
  height: 9em;
  display: flex;
  justify-content: center;
  align-items: center;
}
.icon-link > svg {
  color: white;
}
</style>

<script>
export default {
  name: "Icon",
  props: ["iconName"]
};
</script>
