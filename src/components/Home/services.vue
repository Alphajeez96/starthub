<template>
    <div class="servicediv">
        <div class="services pt-5">
            <h3>Our Services</h3>

        </div>
        <div class="flex-container mt-5">
            <div class="box mx-5 my-2">
                <div class="vector"> 
                <img src="../../../public/Vector.png" class="vetor pt-2"  alt="">
                </div>
                <h5 class="boxheader mt-3">TALENT DEVELOPMENT</h5>
                <p>We transform local talents into software developers and <br>
                 connect them to opportunities globally.
                 </p>
                   <button type="button" class="btn btn-outline-secondary cardbtn">BECOME A DEVELOPER</button>

            </div>
            <div class="box mx-5 my-2">
                 <div class="vector"> 
                <img src="../../../public/Vector 1.png" class="vetor pt-2"  alt="">
                </div>
                 <h5 class="boxheader mt-3">SOFTWARE DEVELOPMENT</h5>
                 <p>We help organisations solve complex problems through <br>
                 tailored web and Android solutions we build for them.
                 </p>
                 <button type="button" class="btn btn-outline-secondary cardbtn">TALK TO US</button>

            </div>

        </div>
         <div class="flex-container mt-5">
            <div class="box mx-5 my-2">
                <div class="vector"> 
                <img src="../../../public/Group.png" class="vetor pt-2"  alt="">
                </div>
                <h5 class="boxheader mt-3">WORKSPACE</h5>
                <p>Your best work happens here. <br>
                Start Innovation Hub helps you make a living and a life on <br>
                your terms.
                 </p>
                   <button type="button" class="btn btn-outline-secondary cardbtn">GET A SPACE</button>

            </div>
            <div class="box mx-5 my-2">
                 <div class="vector"> 
                <img src="../../../public/Group 2.png" class="vetor pt-2"  alt="">
                </div>
                 <h5 class="boxheader mt-3">STARTUP BUSINESS</h5>
                 <p> Start Innovation Hub is a place where Angels meet<br>
                 early-stage entrepreneurs.<br>
                 Take advantage of our network to start that business.
                 </p>
                 <button type="button" class="btn btn-outline-secondary cardbtn">INVEST</button>

            </div>

        </div>
        <div class="servicebg">
            
        </div>

    </div>

</template>


<style scoped>
.servicebg{
    
}
.cardbtn{
    border:1px solid #071878 !important;
    width: 173px;
height: 43px;
/* border: 1px solid #071878; */
box-sizing: border-box;
border-radius: 2px;
margin:20px 180px 20px 0px;
justify-content: left;
/* margin-right:  100px; */
/* float:left; */
font-size:12px
}

 


div p{
    font-size: 14px;
    text-align:left;
    padding-left:50px;
    padding-top:20px;
    line-height: 26px;
}
.vector{
    margin-left:50px;
    /* justify-content:left; */
    border-radius: 50%;
    background: #EBEEFC;
   width: 50px;
    height: 50px;
    margin-top:30px;
}
    .boxheader{
        color: #484848;
        font-size: 12px;
        text-align: left;
        padding-left:50px;
        line-height:16px;
        /* margin-bottom: 10px */
    }
    .servicediv{
        background: #E5E5E5;
    }
    .services{
        color: #484848;
        /* text-align: center; */
        line-height: 55px;
    }

    .flex-container{
        display: flex;    
        flex-wrap: wrap;
        justify-content: center;
    }
    .box{
       min-width: 35vw;
        min-height: 30vh;
        border: 1px solid #E5E5E5;
        box-shadow: 0px 12px 75px rgba(67, 73, 106, 0.09);
        border-radius: 5px;
        background: white;
        
    }

</style>