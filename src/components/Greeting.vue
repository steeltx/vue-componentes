<template>
  <p>{{ msg }}</p>
</template>

<script>
export default {
  name: "Greeting",
  data() {
    return {
      msg: "Hola mundo",
    };
  },
};
</script>

<style scoped lang="scss">
$color : red;

p {
  color: $color;
}
</style>