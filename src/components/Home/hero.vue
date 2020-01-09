<template>
  <div>
      <div class="bgimage">
          <div>
               <nav class="navbar navbar-expand-lg navbar-light our-nav col-12 pt-5">
    <a class="navbar-brand app-logo">
        <router-link to="/" >
        <img src="../../../public/Group 1.png" alt="">
        </router-link>
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse nav-utilities" id="navbarSupportedContent">

        <ul class="navbar-nav ml-auto">
            <li class="nav-item mx-2">
                <!-- <router-link to="/about" > -->
                <a class="nav-link">ABOUT US</a>
                 <!-- </router-link> -->
            </li>

            <li class="nav-item mx-2">
                <!-- <router-link to="/about" > -->
                <a class="nav-link">WOMEN</a>
                 <!-- </router-link> -->
            </li>

             <li class="nav-item mx-2">
                <!-- <router-link to="/about" > -->
                <a class="nav-link">SERVICES</a>
                 <!-- </router-link> -->
            </li>
           
            <li class="nav-item mx-2">
                <!-- <router-link to="/contact"> -->
                <a class="nav-link" href="">BLOG</a>
                <!-- </router-link> -->
            </li>

             <li class="nav-item mx-2">
                <!-- <router-link to="/contact"> -->
                <a class="nav-link " href="">WORKSPACE</a>
                <!-- </router-link> -->
            </li>

        </ul>
       
    </div>
</nav>
          </div>
          <div  class="col-12 col-md-6  mx-auto welcome-image-words text-center">
                    <h1 class="pt-5  mb-4">We Provide a niche to help you <br class="pt-2"> Ideate, Incubate, Innovate</h1>
                    <p class="mb-3">Start Hub is a lab with business centre facilities and all in one open space for<br>
                       entrepreneurs to leverage on Nigeria’s strength and capitalize on opportunities in the <br>
                        global economy.</p>

                        <button class="btn herobtn btn-outline-light signup-btn mx-2">JOIN US</button>
                    <button class="btn btn-light login-btn mx-2" >HIRE A DEVELOPER</button>
        
                </div>

      </div>
    
                
            </div>
      
 
  
</template>



<style scoped>

    .bgimage{
  min-height: 95vh;
  background: linear-gradient(rgba(4, 9, 32, 0.5), rgba(4, 9, 32, 0.5)),
    url("../../../public/image (1).png");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
    }
    .app-logo{
    margin-left: 7vw;
}
 .nav-link {
    text-decoration: none;
       font-family: sans-serif;
    cursor: pointer
    
}
.nav-utilities{
    margin-right: 7vw;
    
}
/* .app-logo img{
    width: 10vw;
} */
.nav-item .nav-link{
    font-size: 12px;
    color: #ffffff !important;
    line-height: 16px;
    font-family: sans-serif;
    cursor: pointer
}

.nav-item .dropdown-menu .dropdown-item{
    font-size: 12px;
    font-weight: bold;
}
.login-btn{
    font-size: 12px;
    width: 12vw;
    border-radius: 4px;
    height: 7vh ; 
    margin-top: 25px

}
.signup-btn{
    font-size: 12px;
    width: 12vw;
    border-radius: 4px;
     height: 7vh;
      margin-top: 25px
}

.welcome-image-words {
  min-height: 50vh;
  margin-bottom: 13vh;
  padding-top: 60px;
}
.welcome-image-words h1 {
  color: white;
  /* font-weight: bold; */
  font-family: sans-serif;
  font-size: 43px;
  margin-top: 30px
}
.welcome-image-words p {
  color: white;
  line-height: 20px;
  font-size: 13px;
  font-weight: 2px;
}
.request-demo-btn {
  background: #49a347;
  color: white;
  font-size: 12px;
  /* border-radius: 0px; */
}
@media screen and (max-width: 992px) {
    .login-btn,  .signup-btn{
        width: 20vw;
        margin-bottom: 10px;
        
         /* width: 35vw; */
        height:8vh;
        /* display: inline */
    }
     .welcome-image-words h1{
        font-size:25px;
    }
}

@media screen and (max-width: 768px) {
    .login-btn , .signup-btn{
        width: 30vw;
        /* height:10vh; */
        margin-bottom: 20px;

        margin-left: 0rem !important;
    }
    .app-logo img {
        width: 20vw;
        height:5vh
    }
    .app-logo {
        margin-left: 0vw;
    }
    .welcome-image-words h1{
        font-size:30px;
    }
   
}
</style>

