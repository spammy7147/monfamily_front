<template>
  <div class="logo-container">
    <div class="logo">
      <nuxt-link class="logo-link" to="/">Monfamily</nuxt-link>
    </div>
    <div  class="logo-empty-space"></div>

    <div class="logo-login-register">
      <div class="box-logo-login">
        <nuxt-link class="logo-login" to="/about">로그인</nuxt-link>
      </div>
      <div class="box-logo-login">
        <nuxt-link class="logo-login" to="/about">회원가입</nuxt-link>
      </div>
    </div>

  </div>
</template>

<style>

.logo-container{
  padding: 10px;
  height: 100px;
  display: flex;
  background-color: blue;
}
.logo-container .logo{
  display: flex;
  background-color: red;
  align-items: center;
  flex-grow: 1;
  flex-basis: 0;
}

.logo-container .logo .logo-link {
  font-size: 50px;
  color: pink;
  text-decoration: none;
}
.logo-container .logo-empty-space{
  display: flex;
  background-color: green;
  flex-grow: 2;
  flex-basis: 0;
}

.logo-container .logo-login-register{
  display: flex;
  align-items: center;
  justify-content: center;
  flex-grow: 1;
  flex-basis: 0;
  background-color: aqua;
}
.logo-container .logo-login-register .box-logo-login{
  background-color: white;
  margin: 10px;
}

.logo-container .logo-login-register .box-logo-login .logo-login{
  font-size: 25px;
  text-decoration: none;
}

</style>
