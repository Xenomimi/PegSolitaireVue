<script setup>
import board from './board.vue';
import ball from './ball.vue';
</script>

<template>
<div class="container">    
    <board id="board-0" class="empty">

    </board>
    <board id="board-1" class="empty">

    </board>
    <board id="board-2" class="box">
        <ball draggable="true" id="ball-2">2</ball>
    </board>
    <board id="board-3" class="box">
        <ball draggable="true" id="ball-3">3</ball>
    </board>
    <board id="board-4" class="box">
        <ball draggable="true" id="ball-4">4</ball>
    </board>
    <board id="board-5" class="empty">

    </board>
    <board id="board-6" class="empty">

    </board>
    <board id="board-7" class="empty">
    
    </board>
    <board id="board-8" class="empty">
    
    </board>
    <board id="board-9" class="box">
        <ball draggable="true" id="ball-9">9</ball>
    </board>
    <board id="board-10" class="box">
        <ball draggable="true" id="ball-10">10</ball>
    </board>
    <board id="board-11" class="box">
        <ball draggable="true" id="ball-11">11</ball>
    </board>
    <board id="board-12" class="empty">
    
    </board>
    <board id="board-13" class="empty">
    
    </board>
    <board id="board-14" class="box">
        <ball draggable="true" id="ball-14">14</ball>
    </board>
    <board id="board-15" class="box">
        <ball draggable="true" id="ball-15">15</ball>
    </board>
    <board id="board-16" class="box">
        <ball draggable="true" id="ball-16">16</ball>
    </board>
    <board id="board-17" class="box">
        <ball draggable="true" id="ball-17">17</ball>
    </board>
    <board id="board-18" class="box">
        <ball draggable="true" id="ball-18">18</ball>
    </board>
    <board id="board-19" class="box">
        <ball draggable="true" id="ball-19">19</ball>
    </board>
    <board id="board-20" class="box">
        <ball draggable="true" id="ball-20">20</ball>
    </board>
    <board id="board-21" class="box">
        <ball draggable="true" id="ball-21">21</ball>
    </board>
    <board id="board-22" class="box">
        <ball draggable="true" id="ball-22">22</ball>
    </board>
    <board id="board-23" class="box">
        <ball draggable="true" id="ball-23">23</ball>
    </board>
    <board id="board-24" class="box">

    </board>
    <board id="board-25" class="box">
        <ball draggable="true" id="ball-25">25</ball>
    </board>
    <board id="board-26" class="box">
        <ball draggable="true" id="ball-26">26</ball>
    </board>
    <board id="board-27" class="box">
        <ball draggable="true" id="ball-27">27</ball>
    </board>
    <board id="board-28" class="box">
        <ball draggable="true" id="ball-28">28</ball>
    </board>
    <board id="board-29" class="box">
        <ball draggable="true" id="ball-29">29</ball>
    </board>
    <board id="board-30" class="box">
        <ball draggable="true" id="ball-30">30</ball>
    </board>
    <board id="board-31" class="box">
        <ball draggable="true" id="ball-31">31</ball>
    </board>
    <board id="board-32" class="box">
        <ball draggable="true" id="ball-32">32</ball>
    </board>
    <board id="board-33" class="box">
        <ball draggable="true" id="ball-33">33</ball>
    </board>
    <board id="board-34" class="box">
        <ball draggable="true" id="ball-34">34</ball>
    </board>
    <board id="board-35" class="empty">
    
    </board>
    <board id="board-36" class="empty">
    
    </board>
    <board id="board-37" class="box">
        <ball draggable="true" id="ball-37">37</ball>
    </board>
    <board id="board-38" class="box">
        <ball draggable="true" id="ball-38">38</ball>
    </board>
    <board id="board-39" class="box">
        <ball draggable="true" id="ball-39">39</ball>
    </board>
    <board id="board-40" class="empty">
    
    </board>
    <board id="board-41" class="empty">
    
    </board>
    <board id="board-42" class="empty">
    
    </board>
    <board id="board-43" class="empty">
    
    </board>
    <board id="board-44" class="box">
        <ball draggable="true" id="ball-44">44</ball>
    </board>
    <board id="board-45" class="box">
        <ball draggable="true" id="ball-45">45</ball>
    </board>
    <board id="board-46" class="box">
        <ball draggable="true" id="ball-46">46</ball>
    </board>
    <board id="board-47" class="empty">
    
    </board>
    <board id="board-48" class="empty">
    
    </board>
</div>

</template>

<style scoped>
.game {
    padding: 0;
    margin: 0;
}
.container {
    display: grid;
    grid-template-columns: repeat(7, 52px);
    grid-template-rows: repeat(7, 52px);
    align-items: center;
    justify-items: center;
    gap: 20px;
    width: max-content;
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

.empty {
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    padding: 20px;
    width: 10px;
    height: 10px;
}
</style>