<template>
  <div>
    <login-top middleTop="注册bilibili"></login-top>
    <login-text
      label="姓名"
      placeholder="请输入姓名"
      style="margin: 4.2vw 0;"
      rules="^.{6,16}$"
    />
    <login-text rules="^.{6,16}$" label="账号" placeholder="请输入账号"></login-text>
    <login-text
      label="密码"
      placeholder="请输入密码"
      type="password"
      rules="^.{6,16}$"
    >
    </login-text>
    <login-btn btn-text="注册"></login-btn>
  </div>
</template>
<script>
import LoginTop from '../components/common/LoginTop'
import LoginText from '../components/common/LoginText'
import LoginBtn from '../components/common/LoginBtn'
export default {
  components: {
    LoginTop,
    LoginText,
    LoginBtn
  }
}
</script>
<style>

</style>
