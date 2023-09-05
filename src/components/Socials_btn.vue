<template lang="">
    <div class="share">
      <!-- btn 1 -->
      <a href="mailto:shanestevensxk9@gmail.com">
        <button class="btn1">
          <i height="30px" width="30px" class="fa-solid fa-envelope email text-white"></i>
          <span class="tooltiptext1">
            <div class="card">
             <img src="https://i.postimg.cc/15R6CLSD/unnamed.jpg" alt="">
            </div>
            <div class="username">shanestevens<br>xk9@gmail.com</div>
          </span>
        </button>
      </a>
   
      <!-- btn 2 -->
      <a target="_blank" href="https://www.linkedin.com/in/shane-stevens-bb9194246/">
        <button class="btn2">
          <i height="30px" width="30px" class="fa-brands fa-linkedin linkedin"></i>
          <span class="tooltiptext2">
            <div class="card">
             <img src="https://i.postimg.cc/7hSS0dnX/1666168478319.jpg" alt="">
            </div>
            <div class="username">@Shane Stevens</div>
          </span>
        </button>
      </a>
        
        <a target="_blank" href="https://github.com/BEASTxk9">
            <button class="btn3">
                <svg height="30px" width="30px" viewBox="0 0 30 30" xmlns="http://www.w3.org/2000/svg" class="git">    <path d="M15,3C8.373,3,3,8.373,3,15c0,5.623,3.872,10.328,9.092,11.63C12.036,26.468,12,26.28,12,26.047v-2.051 c-0.487,0-1.303,0-1.508,0c-0.821,0-1.551-0.353-1.905-1.009c-0.393-0.729-0.461-1.844-1.435-2.526 c-0.289-0.227-0.069-0.486,0.264-0.451c0.615,0.174,1.125,0.596,1.605,1.222c0.478,0.627,0.703,0.769,1.596,0.769 c0.433,0,1.081-0.025,1.691-0.121c0.328-0.833,0.895-1.6,1.588-1.962c-3.996-0.411-5.903-2.399-5.903-5.098 c0-1.162,0.495-2.286,1.336-3.233C9.053,10.647,8.706,8.73,9.435,8c1.798,0,2.885,1.166,3.146,1.481C13.477,9.174,14.461,9,15.495,9 c1.036,0,2.024,0.174,2.922,0.483C18.675,9.17,19.763,8,21.565,8c0.732,0.731,0.381,2.656,0.102,3.594 c0.836,0.945,1.328,2.066,1.328,3.226c0,2.697-1.904,4.684-5.894,5.097C18.199,20.49,19,22.1,19,23.313v2.734 c0,0.104-0.023,0.179-0.035,0.268C23.641,24.676,27,20.236,27,15C27,8.373,21.627,3,15,3z"></path></svg>
                <span class="tooltiptext3">
                  <div class="card">
                 <img src="https://i.postimg.cc/QNkknNZ4/102969628.jpg" alt="">
                  </div>
                  <div class="username">@BEASTxK9</div>
                </span>
              </button>
        </a>
       
      </div>
</template>
<script>

export default {
    components:{
     
    }
}
</script>
<style scoped>
   /* socials */
.share {
    display: flex;
    flex-direction: row;
    gap: 1em;
    transition: .4s ease-in-out;
  }
  .btn1 {
    position: relative;
    width: 3em;
    height: 3em;
    outline: none;
    border: 1px solid white;
    border-radius: 50%;
    background-color: transparent;
    transition: .4s all;
  }
  .btn1 .email {
    margin-top: 0.1em;
    fill: white;
  } 
  .btn1 .tooltiptext1 {
    visibility: hidden;
    width: 6em;
    height: 8em;
    background-color:  #17171794;
    color: white;
    text-align: center;
    border-radius: 10px;
    padding: 1em;
    position: absolute;
    left: -1.5em;
    top: -8em;
    z-index: 1;
    transition: .1s ease-in-out;
  }
  .btn1 .tooltiptext1 .card {
    width: 4em;
    height: 4em;
    background-color: white;
  }
  .btn1 .tooltiptext1 .account {
    margin-top: 1em;
  }
  .btn1 .tooltiptext1 .username {
    font-size: 0.7em;
    margin-top: 1.6em;
    font-weight: bold;
  }
  .btn1:hover .tooltiptext1 {
    transform: translateY(-1em);
    visibility: visible;
  }
  .btn1:hover {
    background-color: #171717;
  }
  .btn1:hover .email {
    fill: white;
  }
  .btn2 {
    position: relative;
    width: 3em;
    height: 3em;
    outline: none;
    border: 1px solid rgb(0 119 181);
    border-radius: 50%;
    background-color: transparent;
    transition: .4s all;
  }
  .btn2 .linkedin {
    margin-top: .25em;
    margin-left: .1em;
    fill: rgb(0 119 181);
    color: rgb(0 119 181);
  }
  .btn2 .tooltiptext2 {
    visibility: hidden;
    width: 6em;
    height: 8em;
    background-color:  #17171794;
    color: white;
    text-align: center;
    border-radius: 10px;
    padding: 1em;
    position: absolute;
    left: -1.5em;
    top: -8em;
    z-index: 1;
    transition: .1s ease-in-out;
  }
  .btn2 .tooltiptext2 .card {
    width: 4em;
    height: 4em;
    background-color: white;
  } 
  .btn2 .tooltiptext2 .account {
    margin-top: 1em;
  }
  .btn2 .tooltiptext2 .username {
    font-size: 0.6em;
    margin-top: 1.6em;
    font-weight: bold;
  }
  .btn2:hover .tooltiptext2 {
    transform: translateY(-1em);
    visibility: visible;
  }
  .btn2:hover {
    background-color: #171717;
  }
  .btn2:hover .linkedin {
    fill: white;
  }
  .btn3 {
    position: relative;
    width: 3em;
    height: 3em;
    outline: none;
    border: 1px solid rgb(255, 255, 255);
    border-radius: 50%;
    background-color: transparent;
    transition: .4s all;
  }
  .btn3 .tooltiptext3 {
    visibility: hidden;
    width: 6em;
    height: 8em;
    background-color:  #17171794;
    color: white;
    text-align: center;
    border-radius: 10px;
    padding: 1em;
    position: absolute;
    left: -1.5em;
    top: -8em;
    z-index: 1;
    transition: .1s ease-in-out;
  }
  .btn3 .tooltiptext3 .card {
    width: 4em;
    height: 4em;
    background-color: white;
  }
  .btn3 .tooltiptext3 .account {
    margin-top: 1em;
  }
  .btn3 .tooltiptext3 .username {
    font-size: 0.7em;
    margin-top: 1.6em;
    font-weight: bold;
  }
  .btn3:hover .tooltiptext3 {
    transform: translateY(-1em);
    visibility: visible;
  }
  .btn3:hover {
    background-color: black;
  }
  .btn3:hover .git {
    fill: rgb(255, 255, 255);
  } 
  svg.git{
    fill: white !important;
  }

  @media only screen and (max-width: 769px){
    .btn1,.btn2,.btn3{
        border: none;
        font-size: 1rem;
    }
    .share{
      justify-content: center;
    }
} 
</style>