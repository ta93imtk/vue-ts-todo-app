<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="こっちはtodo" msg2="123412341234" />
  </div>
</template>

<script>
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Todo",
  components: {
    HelloWorld
  }
};
</script>
