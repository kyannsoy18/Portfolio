<template>
      <nav class="navbar navbar-expand-lg bg-body-secondary sticky-top">
        <div class="container-fluid">
          <a class="navbar-brand me-6 col-md-1text-dark stylish-font1 fs-3">CHRISTIAN</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="row">
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link fs-5" aria-current="page" href="#home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link fs-5" href="#contact">Contact</a>
              </li>
              <li class="nav-item">
                <a class="nav-link fs-5" href="#about">About</a>
              </li>
            </ul>
          </div>
        </div>
        </div>
      </nav>
      <br>
      <br>
      <div id="home" class="container">
        <div class="row">
          <div>
            
          </div>
          <div class="col-md-7" id="description1">

            <h1 class="stylish-font1">
            JAKE.
            </h1>
              <h5 class="align">
                Hi there!!!. I am the developer of this project.... 
               I am a College Student of the Cordova Public College. Major in Programming...
                
               

              </h5>
          </div>
          <div class="col-md-5">
            <img class="image" alt="profile" src="/jake.jpg">
          </div>
        </div>
      </div>
      <br>
      <br>
      <br>
      <div id="skills"></div>

     

     
      
        <div id="contact"></div>
        
        <h2 class="pt-4 mb-4 text-center fw-bold stylish-font1">Reach me on:</h2>

        <div class="container">
            <div class="row justify-content-evenly px-lg-0 px-md-3 px-5">
              
                <div class="col-lg-2 col-md-4 text-center py-4 my-3">
                <a href="https://github.com/LanceTheWeakProgrammer">
                  <img src="/github.png" width="80px" title="Github" class="zoom-in-effect">
                </a>
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3">
                  <a href="https://www.facebook.com/profile.php?id=100089900131835">
                    <img src="/fb.png" width="80px" title="Facebook" class="zoom-in-effect">
                  </a>  
                </div>
                <div class="col-lg-2 col-md-4 text-center py-4 my-3">
                  <a href="https://www.instagram.com/lansyoooo/">
                    <img src="/ig.png" width="80px" title="Instagram" class="zoom-in-effect">
                  </a>  
                </div>
                
                <div class="containder">
                <div class="col-lg-4 col-md-4 text-center py-4 my-3">
                  <a href="mailto:lancejavate2002@gmail.com" class="text-dark text-decoration-none">
                   
                  </a>  
                </div>
                </div>
                <div class="col-lg-4 col-md-4 text-center py-4 my-3">
                  <h5 class="zoom-in-effect fw-bold"><i class="fas fa-phone"></i>  Email: andalanchristianjake@gmail.com</h5>
                </div>
            </div>
        </div>
     

        <div id="about">

          <h2 class="pt-4 mb-4 text-center fw-bold stylish-font1">About me...</h2>

          <div class="container">
            <h5>
              Allow me to introduce myself – I'm Christian Jake Andalan, my goal is to be a developer..
            </h5>
          </div>
          </div>

          <div class="container-fluid bg-white mt-5 footer">
            <div class="row">
                
                <div class="col-lg-4 p-4">
                  
                </div>
                <div class="col-lg-4 p-4">
                    <h5 class="mb-3">Contact me</h5>
                    <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                        <i class="fab fa-twitter me-1"></i> Github
                    </a><br>
                    <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                        <i class="fab fa-facebook me-1"></i> Facebook
                    </a><br>
                    <a href="" class="d-inline-block text-dark text-decoration-none mb-2">
                        <i class="fab fa-instagram me-1"></i> Instagram
                    </a><br>
                </div>
            </div>
        </div>
</template>

<script>

  </script>

<style scoped>
#description1 {
  margin-top: 280px;
}

#description2 {
  margin-top: 200px;
}

h1 {
  font-size: 50px;
  float: top;
  width: 0;
}

@media (max-width: 767px) {
  #description1,
  #description2 {
    margin-top: 0; 
  }
  h1 {
  font-size: 50px;
}
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.stylish-font1 {
  font-family: "Play", sans-serif;
  font-weight: 700;
  font-style: normal;
}

.stylish-font2 {
  font-family: "Dancing Script", cursive;
  font-optical-sizing: auto;
  font-weight: 700;
  font-style: normal;
  font-size: 27px; 
}
.stylish-font3 {
  font-family: "Bebas Neue", sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 60px; 
}
.stylish-font4 {
  font-family: "Playfair Display", serif;
  font-optical-sizing: auto;
  font-weight: 700;
  font-style: normal;
  font-size: 22px; 
}

.image {
    width: 100%; /* Make sure the image fills the container */
    height: auto; /* Maintain aspect ratio */
    border-radius: 50%; /* Create a circular shape */
    float: right;
}

.align {
  text-align: left;
}

</style>