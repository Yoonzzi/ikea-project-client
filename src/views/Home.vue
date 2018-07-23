<template>
  <div class="home">
    <img id="ikea-logo" src="../assets/Ikea_logo.svg">
    <HelloWorld msg="Welcome to Furnishing.help"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>

<style>
#ikea-logo {
  transform: rotate(180deg);
}
</style>
