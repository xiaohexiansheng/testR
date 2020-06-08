<template>
	<div class="dragbox">
		<el-row :gutter="20">
		  <el-col :span="6"><div class="grid-content bg-purple"></div></el-col>
		  <el-col :span="6" :offset="6"><div class="grid-content bg-purple"></div></el-col>
		</el-row>
		<el-row :gutter="20">
		  <el-col :span="6" :offset="6"><div class="grid-content bg-purple"></div></el-col>
		  <el-col :span="6" :offset="6"><div class="grid-content bg-purple"></div></el-col>
		</el-row>
		<el-row :gutter="20">
		  <el-col :span="12" :offset="6"><div class="grid-content bg-purple"></div></el-col>
		</el-row>
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
        this.$router.push('/')
      }
		},
		mounted() {

		}
	}
</script>

<style scoped>

</style>
