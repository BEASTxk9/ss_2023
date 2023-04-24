<template lang="">
   <div id="content" class="container justify-content-center">
<!-- page heading -->
<div class="row">

    <div class="col-sm-12 main-content justify-content-center text-center">

      <!-- type writer -->
      <div class="container typewriter-container">
        <transition name="slide-right" appear>
          <h1 class="typewriter-text">
            <a
              href="#about"
              class="typewrite text-white"
              data-period="2500"
              data-type='[ "Hi there,", "Im Shane,"]'
            >
            </a>
          </h1>
        </transition>
      </div>
      <h2>Aspiring Web Developer & Designer</h2>

        <a href="#about">
            <Scroll_btn></Scroll_btn>
        </a>
      
    </div>

</div>
   </div>

    <!-- bottom page content -->
   <div id="bottom-content" class="container pb-1">
<div class="row">
    <!-- left -->
    <div id="socials" class="col-sm-12 col-md-6 text-start justify-content-start">
    <Socials_btn></Socials_btn>
    </div>
    <!-- right -->
    <div id="my_projects" class="col-sm-12 col-md-6 text-end justify-content-end">
       <h6>MY PROJECTS <Projects></Projects></h6>
    </div>
</div>
   </div>
</template>

<script>
import Scroll_btn from './Scroll_btn.vue';
import Socials_btn from './Socials_btn.vue';
import Projects from './Projects.vue';

export default {
components :{
    Scroll_btn,
    Socials_btn,
    Projects
}
}

// type nwriter effect
var TxtType = function (el, toRotate, period) {
  this.toRotate = toRotate;
  this.el = el;
  this.loopNum = 0;
  this.period = parseInt(period, 10) || 2000;
  this.txt = "";
  this.tick();
  this.isDeleting = false;
};
TxtType.prototype.tick = function () {
  var i = this.loopNum % this.toRotate.length;
  var fullTxt = this.toRotate[i];
  if (this.isDeleting) {
    this.txt = fullTxt.substring(0, this.txt.length - 1);
  } else {
    this.txt = fullTxt.substring(0, this.txt.length + 1);
  }
  this.el.innerHTML = '<span class="wrap">' + this.txt + "</span>";
  var that = this;
  var delta = 200 - Math.random() * 100;
  if (this.isDeleting) {
    delta /= 2;
  }
  if (!this.isDeleting && this.txt === fullTxt) {
    delta = this.period;
    this.isDeleting = true;
  } else if (this.isDeleting && this.txt === "") {
    this.isDeleting = false;
    this.loopNum++;
    delta = 500;
  }
  setTimeout(function () {
    that.tick();
  }, delta);
};
window.onload = function () {
  var elements = document.getElementsByClassName("typewrite");
  for (var i = 0; i < elements.length; i++) {
    var toRotate = elements[i].getAttribute("data-type");
    var period = elements[i].getAttribute("data-period");
    if (toRotate) {
      new TxtType(elements[i], JSON.parse(toRotate), period);
    }
  }
  // INJECT CSS
  var css = document.createElement("style");
  css.type = "text/css";
  css.innerHTML = ".typewrite > .wrap { border-right: 0.08em solid #fff}";
  document.body.appendChild(css);
};
</script>

<style scoped>
#content{
justify-content: center;
align-items: center;
align-content: center;
padding-top:35vh;
font-weight: 500;
letter-spacing: 2px;
text-shadow: 0px 0px 5px rgba(0, 0, 0, 1);
}
/* content borders */
.main-content{
    border-left: 1px solid white;
    border-right: 1px solid white;
}
#bottom-content{
justify-content: center;
align-items: center;
align-content: center;
padding-top:23vh;
font-weight: 500;
letter-spacing: 2px;
}
.typewriter-text, a{
    font-size: 4rem;
    text-decoration: none;
    letter-spacing: 2px;
    padding: 0;
    margin: 0;
  }


  @media only screen and (max-width: 769px){
    .typewriter-text, a{
        font-size: 3rem;
      }
      #content{
        margin-top: -20vh;
      }
      #bottom-content{
        font-size: 0.5rem;
      }

      #my_projects{
        display: none;
      }


} 

@media only screen and (max-width: 575.5px){

      #my_projects{
margin-top: -5vh;
      }
} 
</style>