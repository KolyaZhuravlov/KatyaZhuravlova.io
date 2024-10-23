<template>
	<div class="vika">
		<img  width="500" src="../assets/img/IMG_8747.JPG" alt="Перше фото">
	</div>
</template>

<script>
export default {
	data(){
		return{
			
		}
	}
}
</script>

<style scoped>
.vika {
	display: flex;
    justify-content: space-around;/* Центрируем по горизонтали */
      /* Центрируем по вертикали (если нужно) */
    
}
img {
    max-width: 100%;       /* Адаптивное изображение */
    height: auto;
}
</style>