<template>
  <div class="footer">
    <div class="container">
      <div class="footer_inner">
        <h2 class="footer_paragraph">Статьи каждую неделю</h2>
        <p class="footer_p">
          Больше 90% учеников прошли полный курс и смогли собрать свой первый
          компьютер
        </p>
        <form class="footer_form">
          <input type="text" class="footer_input" placeholder="E-mail" />
          <button class="footer_btn">Подписаться</button>
        </form>
        <ul class="footer_list">
          <li class="footer_item">
            <a href="#" class="footer_item_link">
              <img
                src="../assets/vk.png"
                alt="icon"
                class="footer_img"
                width="50"
                height="50"
              />
            </a>
          </li>
          <li class="footer_item">
            <a href="#" class="footer_item_link">
              <img
                src="../assets/youtube.png"
                alt="icon"
                class="footer_img"
                width="50"
                height="50"
              />
            </a>
          </li>
          <li class="footer_item">
            <a href="#" class="footer_item_link">
              <img
                src="../assets/facebook.png"
                alt="icon"
                class="footer_img"
                width="50"
                height="50"
              />
            </a>
          </li>
          <li class="footer_item">
            <a href="#" class="footer_item_link">
              <img
                src="../assets/insta.png"
                alt="icon"
                class="footer_img"
                width="50"
                height="50"
              />
            </a>
          </li>
        </ul>
        <p class="footer_bottom">Templates #18. More on Figma.info</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
.footer_inner {
  padding-left: 202px;
  padding-right: 202px;
  padding-top: 100px;
  padding-bottom: 50px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.footer_paragraph {
  font-size: 48px;
  color: #ffffff;
  line-height: 67px;
  margin-bottom: 30px;
}
.footer_p {
  font-size: 14px;
  margin-bottom: 40px;
  width: 411px;
  color: #898888;
  text-align: center;
}
.footer_form {
margin-bottom: 30px;
}
.footer_input {
  width: 353px;
  background-color: #1d1c1c;
  opacity: 0.7;
  color: #ffffff;
  border: none;
  border-radius: 16px;
  padding: 10px 30px;
}
.footer_btn {
  background: linear-gradient(94.78deg, #DF5950 11.19%, #451046 93.72%);
  border-radius: 16px;
  border: none;
  color: #ffffff;
  cursor: pointer;
  padding: 10px 30px;
  transform: translateX(-40px);
}
.footer_list {
  display: flex;
  align-items: center;
  margin-bottom: 40px;
}
.footer_item  + .footer_item {
  margin-left: 30px;
}
/* .footer_item_link {
} */
.footer_img {
}
.footer_bottom {
  color: #ffffff;
  opacity: 0.7;
}
</style>