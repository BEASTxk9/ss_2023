<template lang="">
<div class="container">
    <div class="row">
        <h1 class="pb-4">ABOUT</h1>
        <!-- img -->
        <div class="col-sm-12 col-md-6">
          <img id="ss" class="rounded-pill" src="https://i.postimg.cc/8P3Z2Mn2/me3-removebg.png" alt="ss" defer>
        </div>
        <!-- text -->
        <div id="about_me" class="col-sm-12 col-md-6 text-start">
            <p>Hi there, Im Shane Stevens. I grew up in Plumstead. In my schooling years I attended Heathfield Primary and Heathfield High school. During that time I was very active when it came to their extra curriculum activities . A few examples of those activities are Heathfield High Schools annual 24 hour marathon and A-section which is an inter school event used to select Western Province young athletes.<br><br>I matriculated in 2021 and I started studying Web Development in 2022 at Life choices Academy. During my time at life choices I not only learnt about coding but I learnt that my strongest trait is problem solving. I am hard working, self driving and resilient because I enjoy what I do.</p>

            <div id="about-info2" class="container">
                <div class="row">
                  <!-- left -->
                  <div class="col-sm-4">
                    <p>Country: South Africa</p>
                    <p>City: Cape Town</p>
                  </div>
                  <!-- center -->
                  <div class="col-sm-4">
                    <p>Birth: 05/03/2003</p>
                    <p>Criminal Record: None</p>
                  </div>
                  <!-- right -->
                  <div class="col-sm-4">
                    <p>Home language: English</p>
                    <p>Second language: Afrikaans</p>
                  </div>
                </div>
              </div>

            <CV_btn></CV_btn>

        </div>
    </div>
</div>
</template>
<script>
import CV_btn from './CV_btn.vue';

export default {
    components:{
CV_btn
    }
}
</script>
<style scoped>
    #about_me{
        font-size: 1.3rem;
    }

    #about-info2{
        padding: 0;
        margin: 0;
        font-size: 1rem;
    }

    #ss{
      -webkit-filter: grayscale(80%); /* Safari 6.0 - 9.0 */
      filter: grayscale(80%);
      max-height: 80vh;
    }

    @media only screen and (max-width: 767.5px){
      #ss{
        -webkit-filter: grayscale(80%); /* Safari 6.0 - 9.0 */
        filter: grayscale(80%);
        max-height: 50vh;
        padding-bottom: 3vh;
      }

      #about_me{
padding-left: 1rem;
padding-right: 1rem;
      }
  
    }
</style>