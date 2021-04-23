<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Button>0000000000</Button>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import { Button } from "ant-design-vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    Button
  }
};
</script>
