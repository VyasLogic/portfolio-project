<template>
  <!-- Home Page Content -->
  <div class="home">
    <!-- Container -->
    <div class="container">
      <!-- Intro section -->
      <IntroSection />

      <!-- Vertical Divider -->
      <div class="vl"></div>

      <!-- Personal Picture -->
      <PhotoSection />
    </div>
  </div>
</template>

<script>
import IntroSection from "../components/intro-section/intro-section.vue";
import PhotoSection from "../components/photo-section/photo-section.vue";

export default {
  components: {
    IntroSection: IntroSection,
    PhotoSection: PhotoSection,
  },
};
</script>

<style>
.container {
  top: 50%;
  width: 70vw;
  display: flex;
}
.container div {
  -ms-flex: 1; /* IE 10 */
  flex: 1;
}

.vl {
  border-left: 6px solid green;
  height: 500px;
  padding: 30px;
  flex: 0 !important;
}
</style>
