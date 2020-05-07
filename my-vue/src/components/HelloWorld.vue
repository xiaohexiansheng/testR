<template>
	<div class="dragbox">
		<input type="text"v-model="firesName" />
		<input type="text"v-model="secondName"  />
		<p>{{fullName}}</p>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				firesName:1,
				secondName:2
			}
		},
		methods: {
			goTsetDev() {
				this.$router.push('/hello')
			}
		},
		mounted() {

		},
		computed:{
			fullName(){
				return Number(this.firesName)+Number(this.secondName)
			}
		}
	}
</script>

<style scoped>
</style>