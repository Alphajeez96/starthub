<template>
    <div>
         <section class="customers col-11 col-md-11 mx-auto">
                <div class="col-12 customer-review mt-5 ">
                    <h2 class="text-center customer-header">We are trusted by these companies</h2>

                     <div class="col-12 col-md-10 partners-showcase row mx-0 px-0 mx-auto mt-3">
                        <div class="col-3 col-md pt-3">
                            <img src="../../../public/image 3.png" alt="">
                        </div>
                        <div class="col-3 col-md pt-3">
                            <img src="../../../public/image 4.png" alt="">
                        </div>
                       
                        <div class="col-3 p col-md pt-3">
                            <img src="../../../public/image 5.png" alt="">
                        </div>
                        <div class="col-3 col-md pt-3">
                            <img src="../../../public/image 6.png" alt="">
                        </div>
                      
                     </div>
                </div>
         </section>
    </div>
</template>

<style scoped>

.customer-header {
  /* font-weight: bold; */
  color: #484848;
  font-size: 20px
}


.partners-showcase div {
  height: 18vh;
}
.partners-showcase div img {
  /* width: 100%; */
  width:10vw;
  height:7vh;
  vertical-align: middle;
  background: white;
   mix-blend-mode: luminosity;
    opacity: 0.94;
      filter: grayscale(100%);
 
}
@media screen and (max-width: 768px) {
    .customer-header{
        font-size: 24px
    }
}

</style>