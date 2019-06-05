<template>
    <div class="container-fluid" id="footer">
        <div class="row">
            <section class="col-md-4">
                <img src="/images/footerlogo.png" />
            </section>
            <section class="col-md-4">
                <b-nav  justified class="links" style="font-size:14px">
                    <b-nav-item active>關於我們</b-nav-item>
                    <b-nav-item>聯繫我們</b-nav-item>
                    <b-nav-item>下載行程</b-nav-item>
                    <b-nav-item >銀行賬戶</b-nav-item>
                    <b-nav-item class="getridofline" >隱私政策</b-nav-item>
                </b-nav>
            </section>
            <section class="col-md-4" >
                <i class="fab">&#xf39e;</i>
                <i class="fab fa-weixin"></i>
            </section>
        </div>
    </div>

</template>

<script>
export default {

}
</script>

<style scoped>
#footer{
    background-color: #103A5B;
    padding:25px;
    text-align:center;
    color:white;
}

.links a{
    color: white;
    border-right:1px solid white;
    line-height:5px;
    margin-top:10px;
}

.getridofline a{
    border-right:none !important;
}

i.fab {

    font-size:1em;
    border-radius: 50%;
    background-color:white;
    color: #103A5B;
    line-height: 2em;
    width: 2em;
    height: 2em;
    text-align: center;
    display: inline-block;
    transition:0.5s;
    margin:5px;
}

.nav-link{
    padding:0.5rem 0 !important;
}

</style>
