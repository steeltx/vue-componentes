<template>
  <p v-if="age > 25">{{ msg }}</p>
  <p v-else>Debes tener 25 o mas para ver el mensaje</p>
</template>

<script>
export default {
  name: "Greeting",
  props: ["age"],
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