<template>
	<div id="demo">
		11111111111111111111111111
      <p @click="goTsetDev">go</p>
   </div>
</template>

<script>
	export default {
		data() {
			return {
			}
		},
		methods: {
			goTsetDev() {
				this.$toast({ msg: '手机号码不能为空' })
				//this.$router.push('/hello')
			}
		},
		mounted() {

		},
		computed:{
			
		}
	}
</script>

<style scoped>
</style>