<template>
  <div class="app">
    <Navbar />
    <router-view />
    <!-- <Footer /> -->
  </div>
</template>

<script>
import { defineComponent } from "vue";
import Navbar from "@/components/navbar/navbar.vue";
import Footer from "@/components/footer/footer.vue";

export default defineComponent({
  name: "AppLayout",
  components: {
    Navbar,
    Footer,
  },
});
</script>

<style>
.app {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

main {
  flex: 1;
  padding: 20px;
}
</style>
