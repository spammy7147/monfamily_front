<template>

  <div class="nav-group">
    <ul class="nav-container">
      <li class="nav-item">
        <NuxtLink to="/">안녕????</NuxtLink>
      </li>
      <li class="nav-item">
        <NuxtLink to="/about">커뮤니티</NuxtLink>
      </li>
      <li class="nav-item">
        <NuxtLink to="/about">정보</NuxtLink>
      </li>
      <li class="nav-item">
        <NuxtLink to="/about">테스트용</NuxtLink>
      </li>
    </ul>
  </div>


</template>

<style>
.nav-group .nav-container{
  display: flex;
  flex-direction: row;
  width: 100%;
  margin: 0;
  padding: 0;
  list-style-type: none;
}

.nav-group .nav-container .nav-item{
  padding: 15px;
  cursor: pointer;
}
.nav-group .nav-container .nav-item a{
  font-size: 25px;
  color:white;
  text-decoration: none;
  text-align: center;
}


</style>
