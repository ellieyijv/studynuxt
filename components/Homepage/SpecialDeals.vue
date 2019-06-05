<template>
    <div class="container-fluid" id="specildeals">
        <div class="col-md-12 specialtitle" style="text-align:center; padding:50px 0">
            <h4>最新優惠</h4>
            <h5>SPECIAL DEALS</h5>
        </div>
        <div class="container" style="padding-bottom:70px;">
            <div class="row">
                <div v-for="card in cardList" :key="card.id"> 
                    <SpecialDealCard :card="card" class="col-md-4"/>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import SpecialDealCard from '../Homepage/SpecialDealCard'
export default {
    components:{
		SpecialDealCard
    },

    data(){
        return{
            cardList:[{
                id: 1,
                img:"/images/special/aussydney.png",
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 2,
                img:'/images/special/ausclassic.png',
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 3,
                img:'/images/special/aussydmel.png',
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 4,
                img:'/images/special/aus.png',
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 5,
                img:'/images/special/auscans.png',
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },
            {
                id: 6,
                img:'/images/special/auscanssyd.png',
                title:"澳大利亚墨尔本+凯恩斯+悉尼自由行 经典东海岸每城",
                subtitle: "最後機會 立馬下訂",
                price:"$3447 /人起",
                days:"15天14夜"
            },]
        }
    }
    
}
</script>

<style scoped>
#specildeals{
    background-color: #E5E5E5;
    color: #103A5B;
}

.specialtitle h4{
    font-size:18px;
    letter-spacing: 2px;
    font-family: 'PingFang';
}
.specialtitle h5{
   
    font-size:14px;
    letter-spacing: 3px;
    font-family: 'Playfair Display', serif;
    line-height: 3px;
}
</style>
