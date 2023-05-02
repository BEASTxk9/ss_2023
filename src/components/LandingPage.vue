<template lang="">
   <div id="content" class="container justify-content-center">
<!-- page heading -->
<div class="row">

    <div class="col-sm-12 main-content justify-content-center text-center">

      <!-- type writer -->
      <div class="typewriter">{{ text }}</div>
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
    <div  class="col-sm-12 col-md-6 text-end justify-content-end">
       <h6 ><span id="my_projects">MY PROJECTS</span><Projects></Projects></h6>
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
},

data() {
  return {
    text: '',
  };
},
methods: {
  typeWriter() {
    const text = "Hi, I'm Shane Stevens.";
    let i = 0;

    setInterval(() => {
      this.text += text.charAt(i);
      i++;

      if (i > text.length) {
        clearInterval();
      }
    }, 100);
  },
},
mounted() {
  this.typeWriter();
},


}


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

.typewriter {
font-size: 4rem;
font-weight: bold;
transition: all 3s ease-in-out;
text-shadow: 0px 0px 5px rgba(0, 0, 0, 1);
}


  @media only screen and (max-width: 769px){
    .typewriter {
      font-size: 1.5rem;
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