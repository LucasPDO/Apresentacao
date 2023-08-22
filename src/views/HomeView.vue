<template>
  <div class="home">
    <homeApresentacao />
  </div>
</template>

<script>
// @ is an alias to /src
import homeApresentacao from "@/components/homeApresentacao.vue";

export default {
  name: "HomeView",
  components: {
    homeApresentacao,
  },
};
</script>
