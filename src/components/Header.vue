<template>
<header class="header">
    <ul>
        <li><a href="http://localhost:5173/">{{first}}</a></li>
        <li><a href="https://www.youtube.com/watch?v=g73VmfNX258">{{portfolio}}</a></li>
        <li><a class="katya" href="http://localhost:5173/">{{katya}}</a></li>
        <li><a href="https://www.youtube.com/watch?v=g73VmfNX258">{{info}}</a></li>
        <li><a href="https://www.youtube.com/watch?v=g73VmfNX258">{{contacts}}</a></li>
    </ul>
</header>
</template>

<script>
export default {
	data(){
		return{
			first: 'ГОЛОВНА',
			portfolio: 'ПОРТФОЛІО',
			katya: 'KATYA ZHURAVLOVA',
			info: 'ІНФО',
			contacts: 'КОНТАКТИ'
		}
	}
}
</script>

<style scoped>
header {
	display: flex;
	align-items: center;
	height: 155px;
}
.katya{
	display: block;
	width: 200px;
	text-align: center;
}
</style>