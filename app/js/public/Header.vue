<template>
   <div :class="$style.header">
       <span :class="$style.left">
           <em>注册</em>&nbsp;|&nbsp;<em>登录</em>
       </span>
       <btn :class="$style.btnDownload">APP下载</btn>
   </div>
</template>

<script>
import btn from '../core/btn.vue'
export default {
   data() {
       return {}
   },
  components: {
      btn
  }
}
</script>

<style module lang="scss">
.header {
    color: #666;
    height: 100px;
    line-height: 100px;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    font-size: 32px;
    background: #fff url(//timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1551770748208&di=976461cf81045659ebf76af5c119de0f&imgtype=0&src=http%3A%2F%2Fimg.pintu360.com%2Fother%2F20160307%2Feb763bda-5007-4341-9a20-533719ec0b29.jpg) center center no-repeat;
    background-size: auto 150%;
    z-index: 100;
    .left {
        font-size: 28px;
        height: 30px;
        line-height: 30px;
        margin: 17px 0 0 18px;
    }
    .btnDownload {
        float: right;
        font-size: 24px;
        border-width: 0;
        height: 56px;
        line-height: 56px;
        min-width: 120px;
        padding: 0;
        border-radius: 4px;
        margin: 28px 24px 0 0
    }
}
</style>
