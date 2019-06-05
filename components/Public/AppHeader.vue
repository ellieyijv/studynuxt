<template>
  <b-container fluid >
    <b-row align-h="around"  id="header">
      <b-col cols=9>
        <b-row>
          <b-col cols="2" class="contactStyle"></b-col>
          <b-col cols="auto" class="contactStyle">致電 020 7637 7760</b-col>
          <b-col cols="auto" class="contactStyle">電郵 go4funtravel@hotmail.com</b-col>
        </b-row>
      </b-col>
      <b-col cols="1" style="font-size:12px; margin:auto">
        聯系我們
      </b-col>
    </b-row>
    
    <div>
      <b-navbar toggleable="sm" class="offset-1">
        <b-navbar-toggle target="nav-text-collapse"></b-navbar-toggle>
          
        <b-navbar-brand href="#" class="ml-5 ">
             <img src="/images/logo.png" alt="logo">
        </b-navbar-brand>

        <b-collapse id="nav-text-collapse" is-nav>
            
          <b-navbar-nav class="mx-4">
            <b-nav-text>亞洲</b-nav-text>
          </b-navbar-nav >
            <b-navbar-nav class="mx-4">
            <b-nav-text>美洲</b-nav-text>
          </b-navbar-nav>
            <b-navbar-nav class="mx-4">
            <b-nav-text>非洲</b-nav-text>
          </b-navbar-nav>
            <b-navbar-nav class="mx-4">
            <b-nav-text>澳大利亞</b-nav-text>
          </b-navbar-nav>
            <b-navbar-nav class="mx-4">
            <b-nav-text>歐洲</b-nav-text>
          </b-navbar-nav>
                
          <b-navbar-nav class="ml-auto" style="margin-right:130px;">
              <i class="fas fa-search" style="color:black"></i>
          </b-navbar-nav>
           
        </b-collapse>
      </b-navbar>
    </div>
    
  </b-container>
</template>

<script>
import { BContainer, BNavbar } from "bootstrap-vue";

export default {};
</script>

<style  scoped>
#header {
  background-color: #103a5b;
  height: 31px;
  color: white;
}

.contactStyle {
  border-right: 1px solid white;
  font-size:12px;
  line-height: 31px;

}
@media (max-width: 420px) {
  #header {
    display: none;
  }
}

.navbar-text{
  font-size:16px;
  color:#103A5B;
  letter-spacing: 2px;
}

</style>
