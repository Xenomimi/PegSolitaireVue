<script setup>
</script>

<template>
<div class="game">
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
</div>

</template>

<style scoped>
.container {
    display: grid;
    grid-template-columns: repeat(7, 50px);
    grid-template-rows: repeat(7, 50px);
    align-items: center;
    justify-items: center;
    gap: 20px;
}

.box {
    display: flex;
    align-items: center;
    justify-content: center;
    border: 1px solid #666;
    background-color: #ddd;
    border-radius: 50%;
    padding: 20px;
    cursor: move;
    width: 10px;
    height: 10px;
}
</style>
