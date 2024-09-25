<script>
export default {
  data() {
    return { 
        currentSlide: 0,
        totalSlides: 2, // Numero di slide
    };
  },
  methods: {
    nextSlide() {
      // Vai alla slide successiva, ritorna alla prima se sei all'ultima
      this.currentSlide = (this.currentSlide + 1) % this.totalSlides;
    },
    prevSlide() {
      // Vai alla slide precedente, torna all'ultima se sei alla prima
      this.currentSlide =
        (this.currentSlide - 1 + this.totalSlides) % this.totalSlides;
    }
  }

  };
</script>

<template>
  <main>
    <div class="Position-relative">
        <h3 class="py-5 BG2 text-center">
            Do You Have A Construction Project We Can Help With?
        </h3>
        <div class="text-center">
        <button class="B3 Position-absolut">
            GET A FREE QUOTE
        </button>
        </div>
        <div class="container">
            <div class="py-5 text-center">
                <h4>
                    Specialists In Modern Construction
                </h4>
                <hr class="hr">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur vero exercitationem quibusdam quis suscipit,<br>
                   sint velit alias magnam, impedit, iste expedita! Natus, animi esse temporibus voluptatum aut debitis?</p>
            </div>
            <!--Card--> 
            <div class="container d-flex py-2">
                <!--Card1--> 
                <div class="card py-3">
                    <div class="circle text-center py-3">
                        <div class="text-center">
                            <svg xmlns="http://www.w3.org/2000/svg" width="46" height="46" fill="grey" class="bi bi-building" viewBox="0 0 16 16">
                               <path d="M4 2.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5zm3 0a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5zm3.5-.5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5zM4 5.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5zM7.5 5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5zm2.5.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5zM4.5 8a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5zm2.5.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5zm3.5-.5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5z"/>
                               <path d="M2 1a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1zm11 0H3v14h3v-2.5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 .5.5V15h3z"/>
                            </svg>  
                        </div>   
                    </div>
                    <div class="text-center">
                        <h4 class="py-4">Buildings</h4>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est nihil harum ab facilis! Eaque, natus dolore.</p>
                    </div>
                </div>
                 <!--Card2-->    
                <div class="card py-3">
                    <div class="circle text-center py-3">
                        <div class="text-center">
                            <svg xmlns="http://www.w3.org/2000/svg" width="46" height="46" fill="grey" class="bi bi-arrow-repeat" viewBox="0 0 16 16">
                                <path d="M11.534 7h3.932a.25.25 0 0 1 .192.41l-1.966 2.36a.25.25 0 0 1-.384 0l-1.966-2.36a.25.25 0 0 1 .192-.41m-11 2h3.932a.25.25 0 0 0 .192-.41L2.692 6.23a.25.25 0 0 0-.384 0L.342 8.59A.25.25 0 0 0 .534 9"/>
                                <path fill-rule="evenodd" d="M8 3c-1.552 0-2.94.707-3.857 1.818a.5.5 0 1 1-.771-.636A6.002 6.002 0 0 1 13.917 7H12.9A5 5 0 0 0 8 3M3.1 9a5.002 5.002 0 0 0 8.757 2.182.5.5 0 1 1 .771.636A6.002 6.002 0 0 1 2.083 9z"/>
                            </svg> 
                        </div>
                    </div>
                    <div class="text-center">
                        <h4 class="py-4">Renovate</h4>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est nihil harum ab facilis! Eaque, natus dolore.</p>
                    </div>
                </div>
                 <!--Card3-->    
                <div class="card py-3">
                    <div class="circle text-center py-3">
                        <div class="text-center">
                            <svg xmlns="http://www.w3.org/2000/svg" width="46" height="46" fill="grey" class="bi bi-house-door-fill" viewBox="0 0 16 16">
                                <path d="M6.5 14.5v-3.505c0-.245.25-.495.5-.495h2c.25 0 .5.25.5.5v3.5a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5v-7a.5.5 0 0 0-.146-.354L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293L8.354 1.146a.5.5 0 0 0-.708 0l-6 6A.5.5 0 0 0 1.5 7.5v7a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5"/>
                            </svg>  
                        </div>
                    </div>
                    <div class="text-center">
                        <h4 class="py-4">Construct</h4>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est nihil harum ab facilis! Eaque, natus dolore.</p>
                    </div>
                </div>
                 <!--Card4-->    
                <div class="card py-3">
                    <div class="circle text-center py-3">
                        <div class="text-center">
                            <svg xmlns="http://www.w3.org/2000/svg" width="46" height="46" fill="grey" class="bi bi-truck" viewBox="0 0 16 16">
                                <path d="M0 3.5A1.5 1.5 0 0 1 1.5 2h9A1.5 1.5 0 0 1 12 3.5V5h1.02a1.5 1.5 0 0 1 1.17.563l1.481 1.85a1.5 1.5 0 0 1 .329.938V10.5a1.5 1.5 0 0 1-1.5 1.5H14a2 2 0 1 1-4 0H5a2 2 0 1 1-3.998-.085A1.5 1.5 0 0 1 0 10.5zm1.294 7.456A2 2 0 0 1 4.732 11h5.536a2 2 0 0 1 .732-.732V3.5a.5.5 0 0 0-.5-.5h-9a.5.5 0 0 0-.5.5v7a.5.5 0 0 0 .294.456M12 10a2 2 0 0 1 1.732 1h.768a.5.5 0 0 0 .5-.5V8.35a.5.5 0 0 0-.11-.312l-1.48-1.85A.5.5 0 0 0 13.02 6H12zm-9 1a1 1 0 1 0 0 2 1 1 0 0 0 0-2m9 0a1 1 0 1 0 0 2 1 1 0 0 0 0-2"/>
                            </svg>  
                        </div>
                    </div>
                    <div class="text-center">
                        <h4 class="py-4">Exclusive</h4>
                        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Est nihil harum ab facilis! Eaque, natus dolore.</p>
                    </div>
                </div>   
            </div>
        </div>
        <!--BackGround tavolo lavoro-->
        <div class="Curved">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
                <path fill="#FFFFFF" fill-opacity="1" d="M0,64L120,90.7C240,117,480,171,720,165.3C960,160,1200,96,1320,64L1440,32L1440,0L1320,0C1200,0,960,0,720,0C480,0,240,0,120,0L0,0Z"></path>
            </svg>
            <div class="container d-flex">
                <div class="COLOR text-center M">
                    <svg xmlns="http://www.w3.org/2000/svg" width="120" height="120" fill="#fed03d" class="bi bi-suitcase-lg-fill" viewBox="0 0 16 16">
                       <path d="M7 0a2 2 0 0 0-2 2H1.5A1.5 1.5 0 0 0 0 3.5v9A1.5 1.5 0 0 0 1.5 14H2a.5.5 0 0 0 1 0h10a.5.5 0 0 0 1 0h.5a1.5 1.5 0 0 0 1.5-1.5v-9A1.5 1.5 0 0 0 14.5 2H11a2 2 0 0 0-2-2zM6 2a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1zM3 13V3h1v10zm9 0V3h1v10z"/>
                    </svg>
                    <h1>3534</h1>
                    <p class="WHITE">PLANNING APPLICATIONS</p>

                </div>
                <div class="COLOR text-center M">
                    <svg xmlns="http://www.w3.org/2000/svg" width="120" height="120" fill="#fed03d" class="bi bi-building" viewBox="0 0 16 16">
                       <path d="M4 2.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5zm3 0a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5zm3.5-.5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5zM4 5.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5zM7.5 5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5zm2.5.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5zM4.5 8a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5zm2.5.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5zm3.5-.5a.5.5 0 0 0-.5.5v1a.5.5 0 0 0 .5.5h1a.5.5 0 0 0 .5-.5v-1a.5.5 0 0 0-.5-.5z"/>
                       <path d="M2 1a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1zm11 0H3v14h3v-2.5a.5.5 0 0 1 .5-.5h3a.5.5 0 0 1 .5.5V15h3z"/>
                    </svg>
                    <h1>896</h1>
                    <p class="WHITE">COMPLETED PROJECTS</p>
                </div>
                <div class="COLOR text-center M">
                    <svg xmlns="http://www.w3.org/2000/svg" width="120" height="120" fill="#fed03d" class="bi bi-people-fill" viewBox="0 0 16 16">
                        <path d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6m-5.784 6A2.24 2.24 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.3 6.3 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1zM4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5"/>
                    </svg>
                    <h1>172</h1>
                    <p class="WHITE"> TRAINED PROFESSIONALS</p>

                </div>
                <div class="COLOR text-center M">
                    <svg xmlns="http://www.w3.org/2000/svg" width="120" height="120" fill="#fed03d" class="bi bi-globe" viewBox="0 0 16 16">
                        <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8m7.5-6.923c-.67.204-1.335.82-1.887 1.855A8 8 0 0 0 5.145 4H7.5zM4.09 4a9.3 9.3 0 0 1 .64-1.539 7 7 0 0 1 .597-.933A7.03 7.03 0 0 0 2.255 4zm-.582 3.5c.03-.877.138-1.718.312-2.5H1.674a7 7 0 0 0-.656 2.5zM4.847 5a12.5 12.5 0 0 0-.338 2.5H7.5V5zM8.5 5v2.5h2.99a12.5 12.5 0 0 0-.337-2.5zM4.51 8.5a12.5 12.5 0 0 0 .337 2.5H7.5V8.5zm3.99 0V11h2.653c.187-.765.306-1.608.338-2.5zM5.145 12q.208.58.468 1.068c.552 1.035 1.218 1.65 1.887 1.855V12zm.182 2.472a7 7 0 0 1-.597-.933A9.3 9.3 0 0 1 4.09 12H2.255a7 7 0 0 0 3.072 2.472M3.82 11a13.7 13.7 0 0 1-.312-2.5h-2.49c.062.89.291 1.733.656 2.5zm6.853 3.472A7 7 0 0 0 13.745 12H11.91a9.3 9.3 0 0 1-.64 1.539 7 7 0 0 1-.597.933M8.5 12v2.923c.67-.204 1.335-.82 1.887-1.855q.26-.487.468-1.068zm3.68-1h2.146c.365-.767.594-1.61.656-2.5h-2.49a13.7 13.7 0 0 1-.312 2.5m2.802-3.5a7 7 0 0 0-.656-2.5H12.18c.174.782.282 1.623.312 2.5zM11.27 2.461c.247.464.462.98.64 1.539h1.835a7 7 0 0 0-3.072-2.472c.218.284.418.598.597.933M10.855 4a8 8 0 0 0-.468-1.068C9.835 1.897 9.17 1.282 8.5 1.077V4z"/>
                    </svg>
                    <h1>19</h1>
                    <p class="WHITE"> INTERNATIONAL OFFICES</p>
                    
                </div>

            </div>
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
                <path fill="#FFFFFF" fill-opacity="1" d="M0,224L120,197.3C240,171,480,117,720,128C960,139,1200,213,1320,250.7L1440,288L1440,320L1320,320C1200,320,960,320,720,320C480,320,240,320,120,320L0,320Z"></path>
            </svg>
        </div>
        <!--ESPLORA LAVORI RECENTI-->
        <div class="container">
            <div class="text-center">
                <h1>Explore Recent Work</h1>
                <hr class="hr">
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ratione vero cupiditate commodi ducimus aut rerum, unde, eveniet ullam quasi, nihil dolorum pariatur laborum quae soluta voluptatibus distinctio minima quos alias officia impedit voluptatum dicta eaque? Quos harum id quo asperiores!</p>
            </div>
            <div class="d-flex py-5">
                <!--Img1-->
                <div class="image-cont">
                    <img class="IMG" src="/img/work1.jpg" alt="work1">

                </div>
                <!--Img2-->
                <div class="image-cont">
                    <img class="IMG" src="/img/work2.jpg" alt="work2">

                </div>
                <!--Img3-->
                <div class="image-cont">
                    <img class="IMG" src="/img/work3.jpg" alt="work3">

                </div>
            </div>
            <div class="container text-center py-4">
                    <a href="#"> VIEW ALL PROJECTS</a>
            </div>
        </div>
        <!--OUR CORE VALUES-->
        <div class="grey-BG">
            <div class="container text-center py-5">
                <div>
                    <h1>Our Core Values</h1>
                    <hr class="hr">
                    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptatibus ea aliquam mollitia recusandae aperiam consequatur quidem! Ipsam illo animi cumque amet dolores velit debitis nobis accusantium quod. Incidunt quas neque facilis possimus quia! Expedita magnam nulla illo dolores natus et!</p>
                </div>
                <div class="d-flex py-5">
                    <!--1-->
                    <div class="M">
                       <div class="circle2 C1 py-5">
                        <svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" fill="white" class="bi bi-house-door-fill" viewBox="0 0 16 16">
                           <path d="M6.5 14.5v-3.505c0-.245.25-.495.5-.495h2c.25 0 .5.25.5.5v3.5a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5v-7a.5.5 0 0 0-.146-.354L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293L8.354 1.146a.5.5 0 0 0-.708 0l-6 6A.5.5 0 0 0 1.5 7.5v7a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5"/>
                        </svg>
                       </div> 
                       <div class="py-4">
                           <h5>Great Services</h5>
                           <p>Lorem ipsum dolor sit amet consectetur <br> adipisicing elit. Optio, amet!</p>
                       </div>
                    </div>
                    
                    <!--2-->
                    <div class="M">
                       <div class="circle2 C2 py-5">
                        <svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" fill="white" class="bi bi-gear" viewBox="0 0 16 16">
                           <path d="M8 4.754a3.246 3.246 0 1 0 0 6.492 3.246 3.246 0 0 0 0-6.492M5.754 8a2.246 2.246 0 1 1 4.492 0 2.246 2.246 0 0 1-4.492 0"/>
                           <path d="M9.796 1.343c-.527-1.79-3.065-1.79-3.592 0l-.094.319a.873.873 0 0 1-1.255.52l-.292-.16c-1.64-.892-3.433.902-2.54 2.541l.159.292a.873.873 0 0 1-.52 1.255l-.319.094c-1.79.527-1.79 3.065 0 3.592l.319.094a.873.873 0 0 1 .52 1.255l-.16.292c-.892 1.64.901 3.434 2.541 2.54l.292-.159a.873.873 0 0 1 1.255.52l.094.319c.527 1.79 3.065 1.79 3.592 0l.094-.319a.873.873 0 0 1 1.255-.52l.292.16c1.64.893 3.434-.902 2.54-2.541l-.159-.292a.873.873 0 0 1 .52-1.255l.319-.094c1.79-.527 1.79-3.065 0-3.592l-.319-.094a.873.873 0 0 1-.52-1.255l.16-.292c.893-1.64-.902-3.433-2.541-2.54l-.292.159a.873.873 0 0 1-1.255-.52zm-2.633.283c.246-.835 1.428-.835 1.674 0l.094.319a1.873 1.873 0 0 0 2.693 1.115l.291-.16c.764-.415 1.6.42 1.184 1.185l-.159.292a1.873 1.873 0 0 0 1.116 2.692l.318.094c.835.246.835 1.428 0 1.674l-.319.094a1.873 1.873 0 0 0-1.115 2.693l.16.291c.415.764-.42 1.6-1.185 1.184l-.291-.159a1.873 1.873 0 0 0-2.693 1.116l-.094.318c-.246.835-1.428.835-1.674 0l-.094-.319a1.873 1.873 0 0 0-2.692-1.115l-.292.16c-.764.415-1.6-.42-1.184-1.185l.159-.291A1.873 1.873 0 0 0 1.945 8.93l-.319-.094c-.835-.246-.835-1.428 0-1.674l.319-.094A1.873 1.873 0 0 0 3.06 4.377l-.16-.292c-.415-.764.42-1.6 1.185-1.184l.292.159a1.873 1.873 0 0 0 2.692-1.115z"/>
                        </svg>
                       </div> 
                       <div class="py-4">
                           <h5>Great Services</h5>
                           <p>Lorem ipsum dolor sit amet consectetur <br> adipisicing elit. Optio, amet!</p>
                       </div>   
                    </div>
                    
                    <!--3-->
                    <div class="M">
                       <div class="circle2 C3 py-5">
                        <svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" fill="white" class="bi bi-people-fill" viewBox="0 0 16 16">
                            <path d="M7 14s-1 0-1-1 1-4 5-4 5 3 5 4-1 1-1 1zm4-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6m-5.784 6A2.24 2.24 0 0 1 5 13c0-1.355.68-2.75 1.936-3.72A6.3 6.3 0 0 0 5 9c-4 0-5 3-5 4s1 1 1 1zM4.5 8a2.5 2.5 0 1 0 0-5 2.5 2.5 0 0 0 0 5"/>
                        </svg>
                       </div> 
                       <div class="py-4">
                           <h5>Great Services</h5>
                           <p>Lorem ipsum dolor sit amet consectetur <br> adipisicing elit. Optio, amet!</p>
                       </div>
                    </div>
                    
                    <!--4-->
                    <div class="M">
                        <div class="circle2 C4 py-5">
                            <svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" fill="white" class="bi bi-lightbulb" viewBox="0 0 16 16">
                                <path d="M2 6a6 6 0 1 1 10.174 4.31c-.203.196-.359.4-.453.619l-.762 1.769A.5.5 0 0 1 10.5 13a.5.5 0 0 1 0 1 .5.5 0 0 1 0 1l-.224.447a1 1 0 0 1-.894.553H6.618a1 1 0 0 1-.894-.553L5.5 15a.5.5 0 0 1 0-1 .5.5 0 0 1 0-1 .5.5 0 0 1-.46-.302l-.761-1.77a2 2 0 0 0-.453-.618A5.98 5.98 0 0 1 2 6m6-5a5 5 0 0 0-3.479 8.592c.263.254.514.564.676.941L5.83 12h4.342l.632-1.467c.162-.377.413-.687.676-.941A5 5 0 0 0 8 1"/>
                        </svg>
                        </div>  
                        <div class="py-4">
                           <h5>Great Services</h5>
                           <p>Lorem ipsum dolor sit amet consectetur <br> adipisicing elit. Optio, amet!</p>
                        </div> 
                    </div>
                </div>
            </div>
            <!--Carosello-->
            <div>
                <div class="carousel-container">
                    <div class="carousel" :style="{ transform: `translateX(-${currentSlide * 100}%)` }">
                        <div class="slide" id="slide1">
                            <h1>Our Home Owners Say</h1>
                            <hr class="hr-slide">
                            <img class="img-slide py-4" src="/img/home-testimonial-113165296.jpg" alt="testimonial1">
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure repellendus voluptatibus id neque earum vero!</p>
                            <h6>HARRY SMITH - NEW HOME OWNER</h6>
                        </div>    
                    </div>
                    <!-- Pulsanti di navigazione -->
                    <button class="prev" @click="prevSlide">❮</button>
                    <button class="next" @click="nextSlide">❯</button>
                </div>
            </div>
            <!--LATEST NEWS-->
            <div class="py-5">
                <div class="text-center">
                    <h1>Latest News</h1>
                    <hr class="hr2">
                    <p class="py-4">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Libero repellat expedita amet incidunt corporis quo alias, magnam mollitia similique at. <br>
                       Lorem, ipsum dolor sit amet consectetur adipisicing elit. Laborum labore voluptates nemo ut sequi, autem maiores eligendi minima quidem delectus.
                    </p>
                </div>
                <div class="d-flex container py-5">
                    <!--1-->
                    <div class="Card-Latest">
                        <div>
                            <img class="img-latest" src="/img/blog-post-134132600-600x362.jpg" alt="img1">
                        </div>
                        <div class="P">
                            <h3>Redeveloping Florida's <br> Remote Southern Coast</h3>
                            <p>December 7th, 2015</p>
                            <hr>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Soluta corporis optio, ipsa et vero maxime quisquam. Voluptate ipsa amet soluta?</p>
                        </div>

                    </div>
                    <!--2-->
                    <div class="Card-Latest">
                        <div>
                            <img class="img-latest" src="/img/blog-post-92486644-600x362.jpg" alt="img1">
                        </div>
                        <div class="P">
                            <h3>How We Manage Large <br> Construction Projects</h3>
                            <p>December 7th, 2015</p>
                            <hr>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Soluta corporis optio, ipsa et vero maxime quisquam. Voluptate ipsa amet soluta?</p>
                        </div>

                    </div>
                    <!--3-->
                    <div class="Card-Latest">
                        <div>
                            <img class="img-latest" src="/img/blog-post-332773904-600x362.jpg" alt="img1">
                        </div>
                        <div class="P">
                            <h3>Future proofing a modern <br> home</h3>
                            <p>December 6th, 2015</p>
                            <hr>
                            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Soluta corporis optio, ipsa et vero maxime quisquam. Voluptate ipsa amet soluta?</p>
                        </div>

                    </div>
                </div>
                <div class="container text-center py-5">
                        <div>
                            <a class="a" href="">VIEW ALL ARTICLES</a>
                        </div>

                </div>
            </div>
        </div>
        <!--TRUSTED PARTNERS-->
        <div>
            <div class="container text-center py-5">
                <h1>Trusted Partners</h1>
                <hr class="hr">
                <p class="py-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptates, sapiente distinctio esse quae nobis magni modi architecto culpa eos numquam, autem tenetur possimus neque, dolor aperiam reiciendis sed rem. Reprehenderit nostrum labore quisquam iusto ipsa!</p>
            </div>
            <div class="container d-flex py-3">
                <!--1-->
                <div>
                    <img class="M img-Partners PB " src="/img/LOGO1.png" alt="LOGO1">
                </div>
                <!--2-->
                <div>
                    <img class="M img-Partners PB" src="/img/LOGO2.png" alt="logo2">
                </div>
                <!--3-->
                <div>
                    <img class="M img-Partners PB" src="/img/LOGO3.png" alt="logo2">
                </div>
                <!--4-->
                <div>
                    <img class="M img-Partners PB" src="/img/LOGO4.png" alt="logo2">
                </div>
                <!--5-->
                <div>
                    <img class="M img-Partners PB" src="/img/LOGO5.png" alt="logo2">
                </div>
            </div>
        </div>    
    </div>
  </main>
</template>

<style lang="scss" scoped>
@use '../assets/scss/partials/variables' as *;

.BG2{
    background-color: #fed03d;  
}
.B3{
    background-color: black;
    color: white;
    height: 40px;
    border: 1px solid white;
}
.hr{
    width: 20%;
    margin-left: 530px;
    margin-top: 30px;
    color: #fed03d;
    border: 3px solid #fed03d;
}
.card{
    height: 350px;
    width: 25%;
    margin-left: 10px;
    background-color: #f5f5f5;
    border: 1px solid #f5f5f5;
    margin-bottom: 100px;
}
.circle{
    height: 80px;
    width: 80px;
    border-radius: 50%;
    border: 1px solid grey;
    margin: 0 auto;
}
.Position-relative{
    position: relative;
}
.Position-absolut{
    position: absolute;
    left: 45%;
    top: 3%;
}
.Curved{
    background-image: url('../img/home.jpg');
    height: 980px;
}
.COLOR{
    color: #fed03d;
}
.WHITE{
    color: white;
}
.M{
    margin: 0 auto;
}
.image-cont{
    height: 400px;
    width: 400px;
    
    border: 10px solid white;
    margin: 0 auto;
}
.IMG{
    height: 400px;
}
a{
    text-decoration: none;
    color: black;
}
.grey-BG{
    background-color: #f5f5f5;
}
.circle2{
    height: 200px;
    width: 200px;
    border-radius: 50%;
    margin: 0 auto;
}
.C1{
    background-color: #4ea4a5;
}
.C2{
    background-color: #4e6da5;
  
}
.C3{
    background-color: #f6722a;

}
.C4{
    background-color: #a7cf47;

}
//CAROUSEL 
.carousel-container {
  width: 100%;
  height: 100vh; 
  padding-bottom: 100px;
  overflow: hidden;
  position: relative;
}
.carousel {
  display: flex;
  width: 100%; 
  height: 100%;
  transition: transform 5s ease;
  }
  .slide {
  width: 100%; 
  height: 100vh;
  display: flex; 
  flex-direction: column; 
  align-items: center;
  justify-content: center;
  color: white; 
  background-size: cover;
  background-position: center;
}
#slide1 {
  background-image: url('img/home-parallax-144609983.jpg');
}
#slide2{
  background-image: url('img/home-parallax-144609983.jpg');
}
button {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(0, 0, 0, 0.5);
  color: white;
  border: none;
  padding: 10px;
  cursor: pointer;
  font-size: 1.5rem;
}
.prev {
  left: 10px;
}

.next {
  right: 10px;
}
//fine carousel 
.img-slide{
    border-radius: 50%;
}
.hr-slide{
    width: 20%;
    margin-top: 30px;
    color: #fed03d;
    border: 3px solid #fed03d;
}
.hr2{
    width: 20%;
    margin-left: 700px;
    margin-top: 30px;
    color: #fed03d;
    border: 3px solid #fed03d;
}
.Card-Latest{
    background-color: white;
    height: 600px;
    width: 30%;
    margin: 0 auto;
    border: 2px solid #f5f5f5;
}
.img-latest{
    width: 100%;

}
.img-Partners{
    width: 100%;

}
.P{
    padding: 20px;
}
.PB{
    padding-bottom: 50px;
}

</style>
