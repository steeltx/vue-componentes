<template>
  <h3>Hey!</h3>
  <button @click="age++">Actualizar edad +1</button>
  <Greeting :age="age" />
  <User :age="age" />
</template>

<script>
import Greeting from "./components/Greeting.vue";
import User from "./components/User";

export default {
  name: "App",
  components: {
    Greeting,
    User,
  },
  data(){
    return{
      age: 20
    }
  }
};
</script>
