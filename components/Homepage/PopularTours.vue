<template>
    <div class="container-fluid" id="populartour">
        <div class="col-md-12" style="text-align:center; margin:70px 0">
            <h4>特別推薦</h4>
            <h5>POPULAR TOUR</h5>
        </div>
        <div class="container">
            <div class="row">
                <div v-for="tour in tourList" :key="tour.id" class="col-md-3" style="margin-bottom:20px;"> 
                    <PopularTourCard :tour="tour" />
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import PopularTourCard from './PopularTourCard'
export default {
    components:{
		PopularTourCard
    },
    data(){
        return{
            tourList: [{
                id: 1,
                img: "/images/popular/popular1.png",
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城...",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 2,
                img: "/images/popular/popular2.png",
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城...",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 3,
                img: "/images/popular/popular3.png",
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城...",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 4,
                img: "/images/popular/popular4.png",
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城...",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 5,
                img: "/images/popular/popular5.png",
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城...",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 6,
                img: "/images/popular/popular6.png",
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城...",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 7,
                img: "/images/popular/popular7.png",
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城...",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 8,
                img: "/images/popular/popular8.png",
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城...",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            }]
        }
    }
}
</script>

<style>
#populartour h4{
    font-size:18px;
    color:#103A5B;
    letter-spacing: 2px;
    font-family: 'PingFang';
}
#populartour h5{
    font-size:14px;
    color:#103A5B;
    font-family: 'Playfair Display', serif;
    letter-spacing: 3px;
    line-height: 3px;
}
</style>
