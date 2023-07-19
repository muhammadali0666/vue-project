<script setup>
import HeroCard from "../components/HeroCard.vue";
</script>

<template>
  <div class="hero">
    <div class="container">
      <div class="hero_inner">
        <div class="hero_top">
          <a href="#" class="header_logo_link">
            <img src="../assets/logo.png" alt="icon" width="40" height="40" />
          </a>

          <div class="header_box">
            <ul class="header_list">
              <li class="header_item">
                <a href="#" class="header_item_link"> Главная </a>
              </li>
              <li class="header_item">
                <a href="#" class="header_item_link"> Курсы </a>
              </li>
              <li class="header_item">
                <a href="#" class="header_item_link"> Расписание </a>
              </li>
              <li class="header_item">
                <a href="#" class="header_item_link"> Преподаватели </a>
              </li>
              <li class="header_item">
                <a href="#" class="header_item_link"> Рассылка </a>
              </li>
              <li class="header_item">
                <a href="#" class="header_item_link"> Контакты </a>
              </li>
            </ul>
            <button class="header_btn">Зайти в кабинет</button>
          </div>
        </div>
        <div class="hero_bottom">
          <h2 class="hero_paragraph">Первый курс по компьютерной сборке</h2>
          <div class="hero_card_wrapper">
            <HeroCard class="hero_card" />
            <HeroCard class="hero_card" />
            <HeroCard class="hero_card" />
            <HeroCard class="hero_card" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<style scoped>
/* .hero_inner {

} */
.hero {
  background-image: url(../assets/hero_bg.png);
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}
.hero_top {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-top: 30px;
  padding-bottom: 30px;
}
.header_box {
  display: flex;
  align-items: center;
}
.header_logo_link {
  color: #ffffff;
}
.header_list {
  display: flex;
  align-items: center;
}
.header_item + .header_item {
  margin-left: 40px;
}
.header_item_link {
  font-size: 14px;
  color: #ffffff;
}
.header_btn {
  background: linear-gradient(94.26deg, #c89afc 9.51%, #7c6afa 90.23%);
  padding: 10px 30px;
  border: none;
  border-radius: 16px;
  margin-left: 200px;
  color: #ffffff;
}
/* hero  */
.hero_bottom {
  padding-left: 202px;
  padding-right: 202px;
  padding-bottom: 200px;
}
.hero_paragraph {
  margin-top: 100px;
  max-width: 920px;
  color: #ffffff;
  font-size: 64px;
  font-weight: 700;

}
.hero_card_wrapper {
  display: flex;
  align-items: center;
  margin-top: 50px;
}
.hero_card + .hero_card {
  margin-left: 20px;
}
</style>