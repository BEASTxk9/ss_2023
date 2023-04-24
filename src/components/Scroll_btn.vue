<template lang="">
        <button class="mouse">
            <div class="scroll"></div> 
          </button>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.mouse {
    width: 25px;
    height: 40px;
    border: 1px solid rgb(196, 196, 196);
    background-color: transparent;
    border-radius: 13px;
    border-bottom-left-radius: 20px;
    border-bottom-right-radius: 20px;
    align-items: center;
    justify-content: center;
    position: relative;
    mix-blend-mode: difference;
  }
  
  .scroll {
    width: 3px;
    height: 10px;
    background-color: rgb(196, 196, 196);
    border-radius: 2px;
    position: absolute;
    left: 10px;
    bottom: 9px;
    animation: move_918 1.5s linear infinite;
    mix-blend-mode: difference;
  }
  
  @keyframes move_918 {
    0% {
      bottom: 9px;
    }
  
    50% {
      bottom: 5px;
    }
  
    100% {
      bottom: 9px;
    }
  }
    
</style>