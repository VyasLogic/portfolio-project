<template>
  <footer>
    <p>&copy; {{ currentYear }} My Website</p>
  </footer>
</template>

<script>
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "Footer",
  setup() {
    const currentYear = ref(new Date().getFullYear());
    return { currentYear };
  },
});
</script>

<style>
footer {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100vw;
  z-index: 200;
  height: 100px;
}
</style>
