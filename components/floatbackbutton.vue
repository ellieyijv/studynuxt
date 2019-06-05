<template>
    <div class="top-scroller js-top-scroller">
    
    <i class="far fa-arrow-up"></i>
  </div>
</template>

<script>
export default {
   
}
</script>

<style>
.top-scroller {
position: fixed;
    bottom: 100px;
    right: 10px;
    font-size: 20px;
    padding: 2px;
    display: none;
    z-index: 2;
    text-align: center;
    cursor: pointer;
    height: 40px;
    width: 40px;
    border-radius: 50%;
    background: rgba(0,0,0,.35);
    color: #fff;
    line-height: 40px;

}
 .top-scroller:hover {
    background: rgba(0,0,0,.6);
}
</style>
