<template lang="">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Grape+Nuts&display=swap" rel="stylesheet">


    <header>
        <a href="#" class="logo">SHANE STEVENS</a>
        <ul id="nav1">
            <li class="mx-2"><a href="#">Home</a></li>
            <li><a href="#about">About</a></li>
            <li class="mx-2"><a id="btn-toggle" class="btn" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasBottom" aria-controls="offcanvasBottom">Projects</a></li>
        </ul>


      </header>


      
</template>

<script>
export default {
    
}

//   _________________
// custom cursor

  // check if file is linked
console.log("...Cursor Running...");
// define variables
let innerCursor = document.querySelector(".inner-cursor");
let outerCursor = document.querySelector(".outer-cursor");
// add even listener to activate function
document.addEventListener("mousemove", moveCursor);
// create function
function moveCursor(e){
    // define variables that reads the cursors movement between the x and y axis
    let x = e.clientX;
    let y = e.clientY;
    // console.log(x, y);

    innerCursor.style.left = `${x}px`;
    innerCursor.style.top = `${y}px`;
    outerCursor.style.left = `${x}px`;
    outerCursor.style.top = `${y}px`;
}
// select all links in the page
let links = Array.from(document.querySelectorAll("a"));
 console.log(links);
// create for each function
// Add 'grow' class to innerCursor when hovering over a link
links.forEach((link) => {
    link.addEventListener("mouseover", () => {
      innerCursor.classList.add("grow");
    });
    
    // Remove 'grow' class from innerCursor when leaving the link
    link.addEventListener("mouseleave", () => {
      innerCursor.classList.remove("grow");
    });
  });

//   _________________
//   Nav Scroll Effect

window.addEventListener("scroll", function(){
    let header = document.querySelector("header");
    header.classList.toggle("sticky", window.scrollY);
})

</script>

<style scoped>
  /* nav */
header{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    transition: all 0.6s ease-in-out;
    font-size: 1.2rem;
    padding: 20px 100px;
    z-index: 1000;
    text-shadow: 0px 0px 10px rgba(0, 0, 0, 0.7);
}
header .logo{
  font-family: 'Grape Nuts', cursive;
    position: relative;
    font-weight: 700;
    color: white;
    font-size: 1.5rem;
    letter-spacing: 2px;
    text-decoration: none;
    transition: 0.10s ease-in-out;
}
header ul{
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
}
header ul li{
position: relative;
list-style: none;
}
/* before scroll */
header ul li a{
    position: relative;margin: 0 15px;
    text-decoration: none;
    color: white;
    letter-spacing: 2px;
    word-spacing: 10px;
    font-weight: 500px;
    transition: all 0.10s ease-in-out;
}
header ul li a:hover{
  color: white;
  mix-blend-mode: difference;
}

/* scroll effect css */
header.sticky{
    padding: 5px 100px;
}
/* after scroll */



@media only screen and (max-width: 769px){
    header .logo{
      display: none;
    }
  
    header{
      width: 200vw;
      overflow-x: scroll;
      display: contents;
    }

    header ul li a{
      padding-top: 0px;
      font-size: 0.9rem;
    }

} 

</style>