<template>
  <div class="icon-container">
    <i class="icon"></i>
  </div>
</template>

<style>
.icon-container {
  display: inline-block;
  position: relative;
  width: 50px;
  height: 50px;
}

.icon {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  font-size: 24px;
  text-align: center;
  line-height: 50px;
  transition: transform 0.2s ease-out;
}

.icon:hover {
  transform: scale(1.2);
}
</style>
