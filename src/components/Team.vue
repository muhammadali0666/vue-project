<template>
  <div class="team">
    <div class="container">
      <div class="team_inner">
        <div class="team_box">
          <img
          src="../assets/icon-heading-2.png"
          alt="icon"
          class="team_img"
          width="127"
          height="127"
        />
        <h2 class="team_paragrapg">Ваши преподаватели</h2>
        </div>

        <ul class="team_list">
          <li class="team_item">
            <img
              src="../assets/pro-1.png"
              alt="icon"
              class="team_item_img"
              width="190"
              height="190"
            />
            <h4 class="team_item_paragraph">Дмитрий Иванов</h4>
            <p class="team_item_p">Специалист по видеокартам</p>
            <button class="team_btn">Биография</button>
          </li>
          <li class="team_item">
            <img
              src="../assets/pro-2.png"
              alt="icon"
              class="team_item_img"
              width="190"
              height="190"
            />
            <h4 class="team_item_paragraph">Дмитрий Иванов</h4>
            <p class="team_item_p">Специалист по видеокартам</p>
            <button class="team_btn">Биография</button>
          </li>
          <li class="team_item">
            <img
              src="../assets/pro-3.png"
              alt="icon"
              class="team_item_img"
              width="190"
              height="190"
            />
            <h4 class="team_item_paragraph">Дмитрий Иванов</h4>
            <p class="team_item_p">Специалист по видеокартам</p>
            <button class="team_btn">Биография</button>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
.team_inner {
  padding-top: 100px;
  padding-bottom: 100px;
  padding-left: 202px;
  padding-right: 202px;
}
.team_box {
  display: flex;
  align-items: center;
  margin-bottom: 50px;
}
/* .team_img {
} */
.team_paragrapg {
  font-size: 48px;
  color: #ffffff;
}
.team_list {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.team_item {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.team_item_img {
  margin-bottom: 30px;
}
.team_item_paragraph {
  margin-bottom: 10px;
  color: #ffffff;
  font-size: 20px;
}
.team_item_p {
  font-size: 14px;
  margin-bottom: 20px;
  color: #ffffff;
}
.team_btn {
  background-color: transparent;
  border: 1px solid #fff;
  border-radius: 16px;
  color: #ffffff;
  padding: 10px 30px;
}
</style>