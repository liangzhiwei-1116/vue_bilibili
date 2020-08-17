<template>
  <div class="btnParent">
    <div class="loginBtn">{{ btnText }}</div>
  </div>
</template>
<script>
export default {
  props: ['btnText']
}
</script>
<style lang="less">
  .btnParent{
    padding: 15px 5px;
  }
  .loginBtn{
    width: 100%;
    height: 45px;
    background-color: #ff9db5;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 16px;
    border-radius: 6.25vw;
  }
</style>
