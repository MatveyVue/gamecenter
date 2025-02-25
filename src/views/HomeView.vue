<template>
<div class="castom">
<input class="search" placeholder="Search">
<img src="/src/components/search.png" width="20px" style="margin-left: -25px; position: absolute; margin-top: 5px;">
</div>
<RouterLink to="/profile">
<img src="https://i.postimg.cc/NM4sxQtq/IMG-5468.jpg" width="35px" style="border-radius: 50px; float: right; margin-top: -35px;">
</RouterLink>

<div style="margin-top: 50px;">
<h2>Tap To Earn</h2>
  <RouterLink to="/tapto" style="text-decoration: none; color: rgb(37, 138, 227); font-family: Geologica; font-size: 14px;">
    <p style="float: right; margin-top: -50px;">Смотреть Все</p>
  </RouterLink>
<div>
  <img src="/src/components/hamster.jpg" width="60px" style="background-color: rgb(45, 45, 45); float: left; border-radius: 15px;">
  <p class="name">Hamster Kombat</p><br>
  <p class="info">Tap To Eern</p>
<a href="https://t.me/hamster_kombat_bot?startapp">
    <button class="open"><b>ОТКРЫТЬ</b></button>
</a>
</div>

<div style="margin-top: 50px;">
  <img src="/src/components/catizen.jpg" width="60px" style="background-color: rgb(45, 45, 45); float: left; border-radius: 15px;">
  <p class="name">Catizen</p><br>
  <p class="info" style="margin-left: -58px;">Tap To Eern</p>
<a href="https://t.me/catizenbot?startapp">
    <button class="open"><b>ОТКРЫТЬ</b></button>
</a>
</div>

<div style="margin-top: 50px;">
  <img src="/src/components/major.jpg" width="60px" style="background-color: rgb(45, 45, 45); float: left; border-radius: 15px;">
  <p class="name">Major</p><br>
  <p class="info" style="margin-left: -42px;">Tap To Eern</p>
<a href="https://t.me/major?startapp">
  <button class="open"><b>ОТКРЫТЬ</b></button>
</a>
</div>

</div>
</template>

<style scoped>
h2 {
  font-family: Geologica;
  color: white;
}
</style>