<template>

  <router-view/>
</template>

<style>
#app {
  font-family: raleway, roboto mono;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #ffffff;
}

/* html skeleton */
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  /* this will remove default cursor */
  cursor: none;
}

::-webkit-scrollbar {
  display: none;
}

body{
  background-color: #171717;
}
section{
  min-height: 100vh;
  padding-top: 5vh;
}

/* cursor css */
.inner-cursor{
  position: fixed;
  left: 10px;
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background-color: white;
  z-index: 5000;

  /* centers mouse pointer */
  transform: translate(-50%, -50%);
  /* change cursor color to differ from background */
  mix-blend-mode: difference;
  /* allows you to click links under div */
  pointer-events: none;
  /* hover effect */
  transition: width 0.5s, height 0.5s ease-in-out !important;
}
/* inner cursor will grow when hovering over a link */
.inner-cursor.grow{
  width: 25px;
  height: 25px;
  transition: width 0.5s, height 0.5s ease-in-out !important;
}

.outer-cursor{
  position: fixed;
  left: 10px;
  width: 25px;
  height: 25px;
  border: 1px solid white;
  border-radius: 50%;

  /* change cursor color to differ from background */
  mix-blend-mode: difference;
  /* centers mouse pointer */
  transform: translate(-50%, -50%);
     /* allows you to click links under div */
     pointer-events: none;
z-index: 5000;
transition: none !important;
}

@media only screen and (max-width: 769px){

section{
  margin-top: 6vh;
  min-height: 110vh;
}

} 
</style>
