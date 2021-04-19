<template>
  <nav>
    <ul class="nav-container">
      <li class="nav-item">
        <NuxtLink to="/">MonFamily</NuxtLink>
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
  </nav>
</template>

<style>


.nav-container{
  display: flex;
  flex-direction: row;
  width: 100%;
  margin: 0;
  padding: 0;
  list-style-type: none;
}

.nav-item{
  padding: 15px;
  cursor: pointer;
}

.nav-item span {
  color: #cacaca;
}

.nav-item a{
  font-size: 25px;
  color:aqua;
  text-decoration: none;
  text-align: center;
}


</style>
