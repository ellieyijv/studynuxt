<template>
<div >
    <b-card :card="card" class="cardStyle" :img-src="card.img" img-alt="Image" img-top>
        
        <b-card-text class="special-title">{{card.title}}</b-card-text>
        <b-card-text class="special-subtitle">{{card.subtitle}}</b-card-text>  
        <div class="container-fluid">
            <div class="row" style="padding-top:13px;" >
            <b-card-text class="col special-price">{{card.price}}</b-card-text>
         
            <b-button class="special-days col">15天14夜</b-button>
            <b-button class="special-more col">查看更多</b-button>
           
        </div>
    </div>
    </b-card>
    
</div>
</template>

<script>
import { BCard } from 'bootstrap-vue'
export default {
    props:['card']
}
</script>

<style scoped>
.cardStyle{
    width:350px;
    height:386px;
    margin:20px 0;
}

.card img{
    height:210px;
}
.card-body{
    padding:0;
}

.special-title{
    width:306px;
    height:52px;
    font-size:18px;
    color:#103A5B;
    font-weight:bold;
    padding:10px;
}

.special-subtitle{
    color:#AFAFAF;
    font-size:14px;
    padding:10px;
}

.special-price{
    line-height:27px;
    color:#103A5B;
    margin:auto;
}

.special-days{
    background-color:#C2A579;
    color:#FFFFFF;
    border:none;
    border-radius: 0;
}

.special-more{
    background-color: #103A5B;
    color:white;
    border:none;
    border-radius: 0;
}
</style>
