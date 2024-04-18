<script setup lang="ts">
import BoardItem from './boardItem.vue'
</script>

<template>
  <div class="grid place-items-center h-screen">
    <div class="flex flex-col items-center justify-center rounded-lg bg-gray-800">
      <div>
        Next player: <span>X</span>
      </div>
      
      <div>
        Winner: <span>None</span>
      </div>
      
      <button>
        Reset
      </button>

      <div class="grid grid-cols-3 place-items-center m-5 gap-5">
        <BoardItem />
        <BoardItem />
        <BoardItem />
        
        <BoardItem />
        <BoardItem />
        <BoardItem />
        
        <BoardItem />
        <BoardItem />
        <BoardItem />
      </div>
    </div>
  </div>
</template>