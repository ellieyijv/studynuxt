<template>
     <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    img-height="400px"
  >
    <div class="carousel-inner">
            
            <div class="carousel-item active imagebox ">
                <!-- <img class="d-block w-100 img-fluid" src="~/assets/images/carousel.png" alt="Beautiful city view">     -->
                <a href="#hola">
                    <img src="/images/carousel.png" class="img-fluid w-100" style="height:401px;">
                    <div class="imagebox-desc">
                        <div class="container mb-1" style="padding-top:200px;">
                            <p>15天14夜</p>
                            <h5>澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城</h5>
                            <h4>$1899</h4>
                        </div>
                    </div>
                </a>
            </div>

            

    <div class="carousel-item active imagebox ">
                <!-- <img class="d-block w-100 img-fluid" src="~/assets/images/carousel.png" alt="Beautiful city view">     -->
                <a href="#hola">
                    <img src="/images/carousel.png" class="img-fluid w-100" style="height:401px;">
                    <div class="imagebox-desc">
                        <div class="container mb-1" style="padding-top:200px;">
                            <p>15天14夜</p>
                            <h5>澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城</h5>
                            <h4 style="padding-top:20px;">$1899 <span style="font-size:14px; color:#337AB2;">/人起</span></h4>
                        </div>
                    </div>
                </a>
            </div>

            <!-- <div class="carousel-item">
                <a href="#hola">
                    <img src="/images/carousel.png" class="img-fluid w-100" style="height:401px;">
                    <div class="imagebox-desc">
                        <div class="container mb-1" style="padding-top:200px;">
                            <p>15天14夜</p>
                            <h5>澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城</h5>
                            <h4>$1899</h4>
                        </div>
                    </div>
                </a>
            </div>

            <div class="carousel-item">
               <a href="#hola">
                    <img src="/images/carousel.png" class="img-fluid w-100" style="height:401px;">
                    <div class="imagebox-desc">
                        <div class="container mb-1" style="padding-top:200px;">
                            <p>15天14夜</p>
                            <h5>澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城</h5>
                            <h4>$1899</h4>
                        </div>
                    </div>
                </a>
            </div>        -->
    </div>
  </b-carousel>
</template>

<script>
export default {

}
</script>

<style scoped>
.imagebox {
  position: relative;
}
.imagebox .imagebox-desc {
  background-image: linear-gradient(180deg,rgba(51,122,1178,0.2),rgba(16,58,91,1));
  width:455px;
  height:100%;
  color: white;
  font-size: 1.2em;
  left: 0px;
  padding: 0px 40px;
  position: absolute;
  transition: 0.5s padding;
 
  top:0;
 
}

.imagebox-desc p{
  font-size: 16px
}
.imagebox-desc h5{
  font-size:20px;
}
.imagebox-desc H4{
  font-size:24px;
  font-weight: bold;
}
</style>
