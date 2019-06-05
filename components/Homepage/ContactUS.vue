<template>
    <div class="container-fluid">
        <div class="row" style="background-color:#F7F5F1">
            <div class="col-md-5">
                <img src="/images/aboutus.png" style="width:100%"/>
            </div>
            <div class="col-md-7" >
                <div class="row" style="margin-top:50px; color:#897B72">
                    <div class="col-md-3" style="text-align:center">
                        <h4 style="font-size:18px;">關於我們</h4>
                        <h5 style="font-size:14px">ABOUT Us</h5>
                    </div>
                    <div class="col-md-9" >
                        <div class="contactUsText">
                            <P style="font-size:14px">南半球的热情在这里绽放，时尚、优雅、活力、传奇，伴随着慵懒的海湾，狂欢！火车一般是从墨尔本南十字火车站出发，从墨尔本到吉朗。其中从墨尔本到吉朗是火车线，周一至周五高峰时期十几分钟一趟，周六、周日基本每个小时都有一趟。</p>
                            <b-button class="mt-5" variant="outline-secondary">查看更多</b-button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.contactUsText{
    word-wrap: break-word; 
    width: 60%;
    margin:auto;
}

.btn-outline-secondary{
    color:#897B72;
    border-color:#897B72;
}

.btn-outline-secondary:hover{
    color:white;
    background-color:#897B72;
}
</style>
