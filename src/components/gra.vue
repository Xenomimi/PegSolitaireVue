<script setup>
</script>

<template>
<div class="container">
  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">X</div>

  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">X</div>

  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>

  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>

  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>

  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">X</div>

  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">o</div>
  <div draggable="true" class="box">X</div>
  <div draggable="true" class="box">X</div>
</div>
</template>

<style scoped>
.container {
    display: grid;
    grid-template-columns: repeat(7, 1fr);
    justify-items: center;
}

.box {
    border: 1px solid #666;
    background-color: #ddd;
    border-radius: .5em;
    padding: 1rem;
    cursor: move;
    width: 25px;
    text-align: center;
}
</style>
