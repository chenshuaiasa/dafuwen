<template>
  <div>
    <van-nav-bar
      title="其他玩家信息"
      left-text="返回"
      left-arrow
      @click-left="onClickLeft"
    />
  </div>
</template>
<script>
export default {
    data() {
        return {
            temp:""
        }
    },
    methods:{
        onClickLeft:function(){
            this.$router.go(-1);
            console.log("cs");
        }
    }
};
</script>
