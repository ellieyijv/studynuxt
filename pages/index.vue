<template>
	<div>
		<AppHeader/>
		<Carousel />
		<SpecialDeals />
		<PopularTours />
		<Globe />
		<ContactUS />
		<Footer />
		<!-- <back-to-top bottom="50px" right="50px">
			<button type="button" class="btn btn-info btn-to-top"><i class="fab fa-chevron-up"></i></button>
		</back-to-top> -->
	</div>
</template>


<script>
import Carousel from '../components/Homepage/Carousel.vue'
import AppHeader from '../components/Public/AppHeader'
import SpecialDeals from '../components/Homepage/SpecialDeals'
import PopularTours from '../components/Homepage/PopularTours'
import Globe from '../components/Homepage/Globe'
import ContactUS from '../components/Homepage/ContactUS'
import Footer from '../components/Public/Footer'

export default {
	asyncData() {
		return new Promise(resolve => {
			setTimeout(function() {
				resolve({ show: true });
			}, 1000);
		});
	},

	components:{
		Carousel, AppHeader, SpecialDeals, PopularTours, Globe, ContactUS, Footer
	},


	  
};
</script>

<style scoped>
body{
	font-family: 'FangPing' , 'Playfair Display' !important;
	
}
.container-fluid {
	padding-left:0 !important;
	padding-right:0 !important;
}

.btn-to-top {
  width: 60px;
  height: 60px;
  padding: 10px 16px;
  border-radius: 50%;
  font-size: 22px;
  line-height: 22px;
}

</style>
