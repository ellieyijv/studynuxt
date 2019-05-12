<template>
	<div class="container">
	</div>
</template>

  </div>
</template>

<script>

export default {
	asyncData() {
		return new Promise(resolve => {
			setTimeout(function() {
				resolve({ show: true });
			}, 1000);
		});
	}
};
</script>

<style scoped>
.container {
	font-size: 20px;
	text-align: center;
	padding-top: 100px;
}
</style>
