<script setup lang="ts">
//
</script>

<template>
  <div class="background">
    <div class="container">
      <span class="lennyface">
        ( ͡° ͜ʖ ͡°)
      </span>
    </div>
  </div>
</template>


<style scoped>
.background {
  background: white;
  width: 48rem;
  height: 48rem;
}

.container {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  background: conic-gradient(
    hsl(0, 100%, 50%) 0deg,
    hsl(60, 100%, 50%) 60deg,
    hsl(120, 100%, 50%) 120deg,
    hsl(180, 100%, 50%) 180deg,
    hsl(240, 100%, 50%) 240deg,
    hsl(300, 100%, 50%) 300deg,
    hsl(0, 100%, 50%) 360deg
  );
  color: transparent;
  background-clip: text;
}

.lennyface {
  font-family: Arial, sans-serif;
  font-size: 16em;
  transform: scaleY(1.2) translateY(-6%);
}
</style>
