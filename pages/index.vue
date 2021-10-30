<template>
  <div class="container">
    <div class="home_content">
      <p class="home_content-ttl"><strong>生徒一覧</strong></p>
      <NuxtLink to="/students/">生徒の情報を見る</NuxtLink>
    </div>
    <div class="home_content">
      <p class="home_content-ttl"><strong>管理者</strong></p>
      <NuxtLink to="/management/">管理画面を見る</NuxtLink>
    </div>
  </div>
</template>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.home_content {
  margin: 20px;
}
.home_content-ttl {
  font-size: 20px;
  margin-bottom: 0px;
}
</style>