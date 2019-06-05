<template> 
    <div class="hovereffect" :tour="tour" >
        <img class="img-responsive" :src="tour.img" alt="">
        
        <div class="bottomtitle">
            <p  style="font-size:16px; color:white">{{ tour.title }}</p>  
        </div>
        <div class="slider" >
            <div>
                <p style="font-size:14px">{{tour.days}}</p>
                <p style="font-size:16px">{{tour.title}}</p>
                <p style="font-size:20px">{{tour.price}}</p>
            </div>
            
        </div>
    </div>

</template>

<script>
export default {
    props: ['tour'],
    data(){
        return{
            hover: false,
           
        }
    },
    
      
}
</script>

<style scoped>

.hovereffect{
    position:relative;
    width: 255px;
    height: 180px;
}

.bottomtitle{
    position: absolute;
    bottom: 0;
    left:0;
    width: 100%;
    height: 50%;  
    transition: all 2s ease-in;
    background-image:linear-gradient(180deg,hsla(0,0%,100%,0),rgba(1,1,1,1));
}
.bottomtitle p{
    bottom:0;
    position:absolute;
    left:5px;
    top:40%;
}

.hovereffect .slider {
    overflow-y: hidden;
    position: absolute;
    background:linear-gradient(180deg,hsla(0,0%,100%,0),rgba(1,1,1,1));;
    bottom:0;
    left:0;
    height:0%;
    color:white;
    transition: all .5s ease-out
}

.hovereffect:hover .slider {

    transition-property: all;
	transition-duration: 1s;
    transition-timing-function: cubic-bezier(0, 1, 0.5, 1);
    overflow-y: hidden;
	height: 100%; 
}

.hovereffect:hover .bottomtitle {
    display: none;
}




</style>
