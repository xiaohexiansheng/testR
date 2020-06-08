<template>
  <div class="box">
    <transition name="fade">
      <div class="little-tip" v-show="showTip">
        <img src="/success.png" alt="" width="36" v-if="type=='success'" />
        <img src="/fail.png" alt="" width="36" v-if="type=='fail'" />
        <img src="/warning.png" alt="" width="36" v-if="type=='warning'" />
        <img src="/loading.png" alt="" width="36" v-if="type=='loading'" class="loading" />
        <span>{{msg}}</span>
      </div>
    </transition>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        showTip: true,
        msg: '',
        type: ''
      }
    },
    mounted() {
      setTimeout(() => {
        this.showTip = false
      }, 1500)
    },
    beforeCreate(){
    	console.log(11)
    }
  }
</script>
<style  scoped>
  /* 样式略 */
</style>
