<template>
  <div class="home">
    <login></login>
  </div>
</template>

<script>
// @ is an alias to /src
import Login from "@/components/login.vue";

export default {
  name: "Home",
  components: {
    Login
  }
};
</script>
