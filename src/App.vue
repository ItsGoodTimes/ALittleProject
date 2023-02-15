<script setup>
import { ref } from 'vue'

</script>
 
<template>
  <div>
    <!--         Main Menu        -->
    <div id="Main_Menu">
      <p>Rock Paper Scissor!</p>
      <button>Start Game!</button>
    </div>

    <!--         Game Interface    -->
    <div id="Game_Interface">
      <div>
        <p>Bot choose : {{ bot }}</p>
        <p>Result : {{ result }}</p>
      </div>
      <div style="columns: 2 ;">
        <p>Player : {{ playerScore }}</p>
        <p>Bot : {{ botScore }}</p>
      </div>
      <div>
        <button>Rock</button> <button>Paper</button> <button>Scissor</button>
      </div>
    </div>

  </div>
</template>
 
<style scoped>

</style>