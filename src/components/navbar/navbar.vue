<template>
  <header
    style="
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      z-index: 200;
      height: 100px;
    "
  >
    <nav style="justify-content: center">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav>
  </header>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "Navbar",
});
</script>

<style scoped>
nav {
  background-color: #333;
  color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}

ul {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
}

li {
  margin-right: 20px;
}

a {
  color: #fff;
  text-decoration: none;
  padding: 10px;
  border-radius: 5px;
}

a:hover {
  background-color: #fff;
  color: #333;
}
</style>
