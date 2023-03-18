<template>
  <Layout> </Layout>
  <FloatingNav class="nav-style" />
</template>

<script>
import { defineComponent } from "vue";
import Layout from "@/components/layout/layout.vue";
import FloatingNav from "./components/floating-nav/floating-nav.vue";

export default defineComponent({
  name: "App",
  components: {
    Layout,
    FloatingNav,
  },
});
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Montserrat:600&display=swap");
* {
  margin: 0;
  padding: 0;
  left: 0;
  list-style: none;
  text-decoration: none;
  box-sizing: border-box;
}
body {
  font-family: sans-serif;
  background-position: center;
  background-size: cover;
  height: 100vh;
}
</style>
