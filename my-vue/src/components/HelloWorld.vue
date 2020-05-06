<template>
	<div class="dragbox">
		<p @click="goTsetDev">我是一个testdev11111111222222222222221</p>
	</div>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		methods: {
      goTsetDev(){
        this.$router.push('/hello')
      }
		},
		mounted() {

		}
	}
</script>

<style scoped>
.dragbox{
  width: 200px;
  color: #fff;
  background: #1991FA;
  height: 40px;
  line-height: 40px;
  text-align: center;
}
</style>
