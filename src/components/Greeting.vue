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

<style scoped>
p {
  color: red;
}
</style>