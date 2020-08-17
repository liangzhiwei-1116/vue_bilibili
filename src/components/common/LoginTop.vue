<template>
  <div>
    <div class="LoginTop">
      <div></div>
      <!--字符串的props前不用加:-->
      <div>{{ middleTop }}</div>
      <div></div>
    </div>
  </div>
</template>
<script>
export default {
  props: ['middleTop']
}
</script>
<style lang="less">
  .LoginTop {
    height: 12vw;
    background-color: #fff;
    div {
      flex: 1;
      display: flex;
      justify-content: center;
      align-items: center;
      /*vw单位 可以让长度跟着页面大小变化 px换算是px/视图的宽度×100*/
      font-size: 8vw;
    }
  }
</style>
