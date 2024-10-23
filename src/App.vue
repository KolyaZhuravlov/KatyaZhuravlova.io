<template>
<Header></Header>
<Vika></Vika>
<div class="flex-container">
	<span>ПОРТФОЛІО</span>
</div>
<div class="galery" style="width: 1263px">
	<div>
		<img class="img-katya"  src="../src/assets/img/IMG_8763.JPG">
	</div>
	<div>
		<img class="img-kolya"  src="../src/assets/img/IMG_4396.JPG">
	</div>
</div>
<Baswicon></Baswicon>
</template>

<script>
import Header from './components/Header.vue';
import Vika from './components/Vika.vue';
import Baswicon from './components/Baswicon.vue'

export default {
	components: {Header,
		Vika,
		Baswicon},
	data() {
		return{
			
		}
	}
}
</script>

<style scoped>
.flex-container{
	color: #626262;
	text-align: center;
	font-size: 20px;
	margin-bottom: 50px;
	margin-top: 50px;
}
.galery{
	height: 500px;
	display: flex;          /* Используем Flexbox */
    align-items: center;
	 justify-content: space-around;/* Центрируем по горизонтали */

}
.img-katya {
	max-width: 100%;       /* Адаптивное изображение */
	height: auto;
	width: 500px;
}
.img-kolya{
	width: 350px;
}
</style>
