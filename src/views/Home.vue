<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <h1>你就是一个哈皮</h1>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: "home",
  data() {
    return {
      name: "",
      age: false
    };
  },
  components: {
    // HelloWorld
  }
};
</script>
