<template lang="">
    <button id="btn-toggle" class="btn" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasBottom" aria-controls="offcanvasBottom">/</button>

    <div class="offcanvas offcanvas-bottom" tabindex="-1" id="offcanvasBottom" aria-labelledby="offcanvasBottomLabel">
      <div class="offcanvas-header">
        <h5 class="offcanvas-title" id="offcanvasBottomLabel">MY PROJECTS!</h5>
        <button id="close-project" type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
      </div>
      <div class="offcanvas-body small">

        <section id="projects" class="text-black">
            <div class="container">
              <div class="projects-container pt-5">
                <!-- canvas -->
                <img
                  class="projectimg"
                  data-bs-toggle="modal"
                  data-bs-target="#exampleModal"
                  src="https://i.postimg.cc/FFLJMYFx/Screenshot-2023-10-04-111447.png"
                />
                <!-- portfolio-1 -->
                <img
                  class="projectimg"
                  data-bs-toggle="modal"
                  data-bs-target="#exampleModal2"
                  src="https://i.postimg.cc/g0cz07rc/Screenshot-2023-09-05-115719.png"
                />
        
                <!-- portfolio2 -->
                <img
                  class="projectimg"
                  data-bs-toggle="modal"
                  data-bs-target="#exampleModal3"
                  src="https://i.postimg.cc/GmYg63j6/Screenshot-2023-09-05-115058.png"
                />
                <!-- Roasted Beans -->
                <img
                  class="projectimg"
                  data-bs-toggle="modal"
                  data-bs-target="#exampleModal4"
                  src="https://i.postimg.cc/cHq51Sms/Screenshot-2022-10-10-122005.png"
                />
        <!-- healthtracker -->
                                    <img class="projectimg" data-bs-toggle="modal" data-bs-target="#exampleModal5"
                                        src="https://i.postimg.cc/zfpmdXcL/Screenshot-2022-11-01-142956.png" />
                                                   <!-- we code -->
                    <img class="projectimg" data-bs-toggle="modal" data-bs-target="#exampleModal6"
                    src="https://i.postimg.cc/dVdxYCR8/Screenshot-2023-11-21-123120.png" />

              </div>
            </div>
            <!-- Modal1 -->
            <div
              class="modal fade"
              id="exampleModal"
              tabindex="-1"
              aria-labelledby="exampleModalLabel"
              aria-hidden="true"
            >
              <div class="modal-dialog">
                <div class="modal-content">
                  <div class="modal-header">
                    <h5 class="modal-title" id="exampleModalLabel">Canvas</h5>
                    <button
                      type="button"
                      class="btn-close"
                      data-bs-dismiss="modal"
                      aria-label="Close"
                    ></button>
                  </div>
                  <div class="modal-body">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6">
                          <img
                            class="image"
                            src="https://i.postimg.cc/FFLJMYFx/Screenshot-2023-10-04-111447.png"
                            width="100%"
                          />
                        </div>
                        <div class="col-md-6">
                          This canvas was created using html, css & js. Give it a try!
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="modal-footer">
                    <button
                      type="button"
                      class="vist_btns"
                      data-bs-dismiss="modal"
                    >
                      <a
                        class=""
                        href="https://github.com/BEASTxk9/js-canvas"
                        target="_blank"
                        >Github</a
                      >
                    </button>
                    <button type="button" class="vist_btns">
                      <a
                        class=""
                        href="https://js-canvas-xk9.netlify.app/"
                        target="_blank"
                        >Live</a
                      >
                    </button>
                  </div>
                </div>
              </div>
            </div>
            <!-- Modal2 -->
            <div
              class="modal fade"
              id="exampleModal2"
              tabindex="-1"
              aria-labelledby="exampleModalLabel2"
              aria-hidden="true"
            >
              <div class="modal-dialog">
                <div class="modal-content">
                  <div class="modal-header">
                    <h5 class="modal-title" id="exampleModalLabel2">Advanced-simple Portdolio Template 1</h5>
                    <button
                      type="button"
                      class="btn-close"
                      data-bs-dismiss="modal"
                      aria-label="Close"
                    ></button>
                  </div>
                  <div class="modal-body">
                    <div class="container">
                      <div class="row">
                        <div class="col-md-6">
                          <img
                            class="image"
                            src="https://i.postimg.cc/g0cz07rc/Screenshot-2023-09-05-115719.png"
                           width="100%"
                          />
                        </div>
                        <div class="col-md-6">
                       This is a Advanced-simple portfolio that can be used as a template. It was created using HTML, CSS, BOOTSTRAP and simple JS.
                        </div>
                      </div>
                    </div>
                  </div>
                  <div class="modal-footer">
                    <button
                      type="button"
                      class="vist_btns"
                      data-bs-dismiss="modal"
                    >
                      <a
                        class=""
                        href="
                        https://github.com/BEASTxk9/Shane-Stevens_Vue-Portfolio"
                        target="_blank"
                        >Github</a
                      >
                    </button>
                    <button type="button" class="vist_btns">
                      <a
                        class=""
                        href="https://vue-portfolio-shane-stevens.web.app/"
                        target="_blank"
                        >Live</a
                      >
                    </button>
                  </div>
                </div>
              </div>
            </div>
        <!-- Modal3 -->
                        <div class="modal fade" id="exampleModal3" tabindex="-1" aria-labelledby="exampleModalLabel3"
                            aria-hidden="true">
                            <div class="modal-dialog">
                                <div class="modal-content">
                                    <div class="modal-header">
                                        <h5 class="modal-title" id="exampleModalLabel3">Full Stack</h5>
                                        <button type="button" class="btn-close" data-bs-dismiss="modal"
                                            aria-label="Close"></button>
                                    </div>
                                    <div class="modal-body">
                                        <div class="container">
                                            <div class="row">
                                                <div class="col-md-6">
                                                    <img class="image" src="https://i.postimg.cc/GmYg63j6/Screenshot-2023-09-05-115058.png"
                                                    width="100%">
                                                </div>
                                                <div class="col-md-6">
                                                  This is a fullstack website create with php, wordpress and mysql.
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="modal-footer">
                                        <button style="display:none;" type="button" class="vist_btns" data-bs-dismiss="modal"><a
                                                class=""
                                                href="https://github.com/BEASTxk9/MOCK-DIGITAL-PROFILE/blob/main/index.html"
                                                target="_blank">Github</a></button>
                                        <button type="button" class="vist_btns"><a class=""
                                                href="https://dev-lime-wraps.pantheonsite.io/"
                                                target="_blank">Live</a></button>
                                    </div>
                                </div>
                            </div>
                        </div>
                            <!-- Modal4 -->
                        <div class="modal fade" id="exampleModal4" tabindex="-1" aria-labelledby="exampleModalLabel4"
                            aria-hidden="true">
                            <div class="modal-dialog">
                                <div class="modal-content">
                                    <div class="modal-header">
                                        <h5 class="modal-title" id="exampleModalLabel4">Roasted Beans</h5>
                                        <button type="button" class="btn-close" data-bs-dismiss="modal"
                                            aria-label="Close"></button>
                                    </div>
                                    <div class="modal-body">
                                        <div class="container">
                                            <div class="row">
                                                <div class="col-md-6">
                                                    <img class="image" src="https://i.postimg.cc/cHq51Sms/Screenshot-2022-10-10-122005.png"
                                                        width="100%">
                                                </div>
                                                <div class="col-md-6">E-commerce site that allows you to sign up, login, view profile, add to cart etc...</div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="modal-footer">
                                        <button type="button" class="vist_btns" data-bs-dismiss="modal"><a
                                                class="" href="https://github.com/BEASTxk9/E-commerce-shop-vue"
                                                target="_blank">Github</a></button>
                                        <button type="button" class="vist_btns"><a class=""
                                                href="https://roasted-beans-b99e0.web.app/"
                                                target="_blank">Live</a></button>
                                    </div>
                                </div>
                            </div>
                        </div>
        <!-- modal5 -->
                <div class="modal fade" id="exampleModal5" tabindex="-1" aria-labelledby="exampleModalLabel5"
                            aria-hidden="true">
                            <div class="modal-dialog">
                                <div class="modal-content">
                                    <div class="modal-header">
                                        <h5 class="modal-title" id="exampleModalLabel5">Health Tracker App</h5>
                                        <button type="button" class="btn-close" data-bs-dismiss="modal"
                                            aria-label="Close"></button>
                                    </div>
                                    <div class="modal-body">
                                        <div class="container">
                                            <div class="row">
                                                <div class="col-md-6">
                                                    <img class="image-fluid" src="https://i.postimg.cc/zfpmdXcL/Screenshot-2022-11-01-142956.png" width="100%"
                                                        height="100%">
                                                </div>
                                                <div class="col-md-6">This Health Tracker was created using Vuetify.</div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="modal-footer">
                                        <button type="button" class="vist_btns" data-bs-dismiss="modal"><a
                                                class="" href="https://github.com/BEASTxk9/vuetify-heathtracker"
                                                target="_blank">Github</a></button>
                                        <button type="button" class="vist_btns">
                                            <a class="" href="https://shanestevens-healthtracker.netlify.app/#/"
                                                target="_blank">Live</a></button>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- Modal6 -->
                        <div class="modal fade" id="exampleModal6" tabindex="-1" aria-labelledby="exampleModalLabel6"
                            aria-hidden="true">
                            <div class="modal-dialog">
                                <div class="modal-content">
                                    <div class="modal-header">
                                        <h5 class="modal-title" id="exampleModalLabel6">We Code (Website template)</h5>
                                        <button type="button" class="btn-close" data-bs-dismiss="modal"
                                            aria-label="Close"></button>
                                    </div>
                                    <div class="modal-body">
                                        <div class="container">
                                            <div class="row">
                                                <div class="col-md-6">
                                                    <img class="image-fluid" src="https://i.postimg.cc/dVdxYCR8/Screenshot-2023-11-21-123120.png" width="100%"
                                                        height="100%">
                                                </div>
                                                <div class="col-md-6">
                                                    This projects was created using HTML, CSS, & JS. It is a simple website template.
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="modal-footer">
                                        <button type="button" class="vist_btns" data-bs-dismiss="modal"><a
                                                class="" href="https://github.com/BEASTxk9/WE-CODE"
                                                target="_blank">Github</a></button>
                                        <button type="button" class="vist_btns"><a class=""
                                                href="https://we-code-template.netlify.app/"
                                                target="_blank">Live</a></button>
                                    </div>
                                </div>
                            </div>
                        </div>
                
          </section>

      </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            projects: [
                {
                    id: "1",
                    name: "Property-Finder",
                    image:
                        "https://i.postimg.cc/Mpf9V3Vt/Screenshot-2022-07-20-140846.jpg",
                    url: "https://fastidious-lily-44d13b.netlify.app",
                    description:
                        "This is a property site created using vue in normal HTML. It displays numerous properties that can be bought, sold and rented...The ideal site for planning a holiday.  ",
                    category: "vue",
                },
                {
                    id: "2",
                    name: "Advanced-simple Portdolio Template 1",
                    image:
                        "https://i.postimg.cc/QVGHPMYF/Screenshot-2022-07-20-141912.jpg",
                    url: "https://shane-stevens-portfolio.netlify.app",
                    description:
                        "This is a Advanced-simple portfolio that can be used as a template. It was created using HTML, CSS, BOOTSTRAP and simple JS. ",
                },
                {
                    id: "3",
                    name: "Simple Portfolio Template 1",
                    image:
                        "https://i.postimg.cc/GmYg63j6/Screenshot-2023-09-05-115058.png",
                    url: "https://beastxk9.netlify.app",
                    description:
                        "This is a simple portfolio that can be used as a template. It was created using basic HTML, CSS and BOOTSTRAP5.",
                },
                {
                    id: "4",
                    name: "Area Caluculator",
                    image:
                        "https://i.postimg.cc/R0khqh9X/Screenshot-2022-07-20-141409.jpg",
                    url: "https://endearing-mooncake-eefa89.netlify.app",
                    description:
                        "This site allows your to Calculate the Area of a Triangle.",
                    category: "Java Script",
                },
            ],
        };
    },
};
</script>

<style scoped>
.modal{
  color: black;
}

#btn-toggle {
    background-color: transparent;
    border: 1px solid white;
    color: white;
}

.offcanvas-bottom {
    height: 100vh;
    background-color: #171717;
    background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 304 304' width='304' height='304'%3E%3Cpath fill='%231c1c1c' fill-opacity='0.4' d='M44.1 224a5 5 0 1 1 0 2H0v-2h44.1zm160 48a5 5 0 1 1 0 2H82v-2h122.1zm57.8-46a5 5 0 1 1 0-2H304v2h-42.1zm0 16a5 5 0 1 1 0-2H304v2h-42.1zm6.2-114a5 5 0 1 1 0 2h-86.2a5 5 0 1 1 0-2h86.2zm-256-48a5 5 0 1 1 0 2H0v-2h12.1zm185.8 34a5 5 0 1 1 0-2h86.2a5 5 0 1 1 0 2h-86.2zM258 12.1a5 5 0 1 1-2 0V0h2v12.1zm-64 208a5 5 0 1 1-2 0v-54.2a5 5 0 1 1 2 0v54.2zm48-198.2V80h62v2h-64V21.9a5 5 0 1 1 2 0zm16 16V64h46v2h-48V37.9a5 5 0 1 1 2 0zm-128 96V208h16v12.1a5 5 0 1 1-2 0V210h-16v-76.1a5 5 0 1 1 2 0zm-5.9-21.9a5 5 0 1 1 0 2H114v48H85.9a5 5 0 1 1 0-2H112v-48h12.1zm-6.2 130a5 5 0 1 1 0-2H176v-74.1a5 5 0 1 1 2 0V242h-60.1zm-16-64a5 5 0 1 1 0-2H114v48h10.1a5 5 0 1 1 0 2H112v-48h-10.1zM66 284.1a5 5 0 1 1-2 0V274H50v30h-2v-32h18v12.1zM236.1 176a5 5 0 1 1 0 2H226v94h48v32h-2v-30h-48v-98h12.1zm25.8-30a5 5 0 1 1 0-2H274v44.1a5 5 0 1 1-2 0V146h-10.1zm-64 96a5 5 0 1 1 0-2H208v-80h16v-14h-42.1a5 5 0 1 1 0-2H226v18h-16v80h-12.1zm86.2-210a5 5 0 1 1 0 2H272V0h2v32h10.1zM98 101.9V146H53.9a5 5 0 1 1 0-2H96v-42.1a5 5 0 1 1 2 0zM53.9 34a5 5 0 1 1 0-2H80V0h2v34H53.9zm60.1 3.9V66H82v64H69.9a5 5 0 1 1 0-2H80V64h32V37.9a5 5 0 1 1 2 0zM101.9 82a5 5 0 1 1 0-2H128V37.9a5 5 0 1 1 2 0V82h-28.1zm16-64a5 5 0 1 1 0-2H146v44.1a5 5 0 1 1-2 0V18h-26.1zm102.2 270a5 5 0 1 1 0 2H98v14h-2v-16h124.1zM242 149.9V160h16v34h-16v62h48v48h-2v-46h-48v-66h16v-30h-16v-12.1a5 5 0 1 1 2 0zM53.9 18a5 5 0 1 1 0-2H64V2H48V0h18v18H53.9zm112 32a5 5 0 1 1 0-2H192V0h50v2h-48v48h-28.1zm-48-48a5 5 0 0 1-9.8-2h2.07a3 3 0 1 0 5.66 0H178v34h-18V21.9a5 5 0 1 1 2 0V32h14V2h-58.1zm0 96a5 5 0 1 1 0-2H137l32-32h39V21.9a5 5 0 1 1 2 0V66h-40.17l-32 32H117.9zm28.1 90.1a5 5 0 1 1-2 0v-76.51L175.59 80H224V21.9a5 5 0 1 1 2 0V82h-49.59L146 112.41v75.69zm16 32a5 5 0 1 1-2 0v-99.51L184.59 96H300.1a5 5 0 0 1 3.9-3.9v2.07a3 3 0 0 0 0 5.66v2.07a5 5 0 0 1-3.9-3.9H185.41L162 121.41v98.69zm-144-64a5 5 0 1 1-2 0v-3.51l48-48V48h32V0h2v50H66v55.41l-48 48v2.69zM50 53.9v43.51l-48 48V208h26.1a5 5 0 1 1 0 2H0v-65.41l48-48V53.9a5 5 0 1 1 2 0zm-16 16V89.41l-34 34v-2.82l32-32V69.9a5 5 0 1 1 2 0zM12.1 32a5 5 0 1 1 0 2H9.41L0 43.41V40.6L8.59 32h3.51zm265.8 18a5 5 0 1 1 0-2h18.69l7.41-7.41v2.82L297.41 50H277.9zm-16 160a5 5 0 1 1 0-2H288v-71.41l16-16v2.82l-14 14V210h-28.1zm-208 32a5 5 0 1 1 0-2H64v-22.59L40.59 194H21.9a5 5 0 1 1 0-2H41.41L66 216.59V242H53.9zm150.2 14a5 5 0 1 1 0 2H96v-56.6L56.6 162H37.9a5 5 0 1 1 0-2h19.5L98 200.6V256h106.1zm-150.2 2a5 5 0 1 1 0-2H80v-46.59L48.59 178H21.9a5 5 0 1 1 0-2H49.41L82 208.59V258H53.9zM34 39.8v1.61L9.41 66H0v-2h8.59L32 40.59V0h2v39.8zM2 300.1a5 5 0 0 1 3.9 3.9H3.83A3 3 0 0 0 0 302.17V256h18v48h-2v-46H2v42.1zM34 241v63h-2v-62H0v-2h34v1zM17 18H0v-2h16V0h2v18h-1zm273-2h14v2h-16V0h2v16zm-32 273v15h-2v-14h-14v14h-2v-16h18v1zM0 92.1A5.02 5.02 0 0 1 6 97a5 5 0 0 1-6 4.9v-2.07a3 3 0 1 0 0-5.66V92.1zM80 272h2v32h-2v-32zm37.9 32h-2.07a3 3 0 0 0-5.66 0h-2.07a5 5 0 0 1 9.8 0zM5.9 0A5.02 5.02 0 0 1 0 5.9V3.83A3 3 0 0 0 3.83 0H5.9zm294.2 0h2.07A3 3 0 0 0 304 3.83V5.9a5 5 0 0 1-3.9-5.9zm3.9 300.1v2.07a3 3 0 0 0-1.83 1.83h-2.07a5 5 0 0 1 3.9-3.9zM97 100a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0-16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-48 32a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm32 48a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-16 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm32-16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0-32a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16 32a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm32 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0-16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-16-64a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16 0a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16 96a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16-144a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0 32a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16-32a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16-16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-96 0a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16-32a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm96 0a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-16-64a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16-16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-32 0a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0-16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-16 0a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-16 0a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-16 0a3 3 0 1 0 0-6 3 3 0 0 0 0 6zM49 36a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-32 0a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm32 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zM33 68a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16-48a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0 240a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16 32a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-16-64a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-16-32a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm80-176a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16 0a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-16-16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm32 48a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16-16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0-32a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm112 176a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm-16 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zM17 180a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0 16a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm0-32a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16 0a3 3 0 1 0 0-6 3 3 0 0 0 0 6zM17 84a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm32 64a3 3 0 1 0 0-6 3 3 0 0 0 0 6zm16-16a3 3 0 1 0 0-6 3 3 0 0 0 0 6z'%3E%3C/path%3E%3C/svg%3E");
    color: white;
    z-index: 5000;
}

#close-project {
    background-color: grey;
}

.projects-container {
    display: flex;
    flex-wrap: wrap;
    gap: 30px;
    justify-content: space-between;
}

.projectimg {
    width: 40%;
    box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.6);
    transition: all 0.3s ease-in-out;
    -webkit-filter: grayscale(100%);
    filter: grayscale(100%);
}

.projects-container img {
    max-height: 400px;
    flex-grow: 1;
    object-fit: cover;
    transition: all 0.5s ease-in-out;
}

.projectimg:hover {
    opacity: 1;
    background-color: blue;
    width: 50%;
    box-shadow: 10px 10px 26px rgba(0, 0, 0, 1);
    transition: 1s ease-in-out;
    -webkit-filter: grayscale(0%);
    filter: grayscale(0%);
}

.image {
    margin-top: 0rem;
}

#other-links {
    overflow-x: hidden;
}

.vist_btns{
  background-color: #171717;
  color: white;
  padding: 10px;
  border-radius: 5px;
}
.vist_btns a{
  color: white;
  text-decoration: none;
  font-weight: bold;
}

@media only screen and (max-width: 767px) {
    .projects-container {
        display: flex;
        flex-wrap: wrap;
        gap: 10px;
        justify-content: space-between;
    }
}
@media only screen and (max-width: 769px){
  #btn-toggle{
    display: none;
  }
}
</style>