<script setup lang="ts">
//
</script>

<template>
  <div class="layer1">
    <div class="layer2">
      <div class="lennyface">
        ( ͡° ͜ʖ ͡°)
      </div>
    </div>
  </div>
</template>


<style scoped>
.layer1 {
  position: relative;
  height: 100%;
  width: 100%;
  overflow: hidden;
}

.layer1::before {
  position: absolute;
  content: "";
  z-index: -1;
  display: inline-block;
  width: 100%;
  height: 100%;
  background-size: 100% 100%;
  background: conic-gradient(
    hsl(0, 100%, 50%) 0deg,
    hsl(60, 100%, 50%) 60deg,
    hsl(120, 100%, 50%) 120deg,
    hsl(180, 100%, 50%) 180deg,
    hsl(240, 100%, 50%) 240deg,
    hsl(300, 100%, 50%) 300deg,
    hsl(0, 100%, 50%) 360deg
  );
  transform: rotate(-15deg);
}

.layer2 {
  height: 100%;
  width: 100%;
  background-color: white;
  mix-blend-mode: screen;
  display: flex;
  justify-content: center;
  align-items: center;
}

.lennyface {
  font-family: Arial, sans-serif;
  transform: scaleY(1.2) translateY(-6%);
  font-size: 70vw;
}
</style>
