<template>
  <div class="proccess">
    <div class="container">
      <div class="proccess_inner">
        <button class="proccess_btn">Заказать курс</button>
        <ul class="proccess_list">
          <li class="proccess_item">
            <p class="proccess_item_p">Учеников всего:</p>
            <p class="proccess_item_p_right">200</p>
          </li>
          <li class="proccess_item">
            <p class="proccess_item_p">Успешно закончили курс:</p>
            <p class="proccess_item_p_right">190</p>
          </li>
        </ul>
        <div class="proccess_end">
          <p class="proccess_end_p">
            Заработано учениками:
            <span class="proccess_end_p_right"> 400 000₽ </span>
          </p>
        <div class="proccess_end_span_wrapper">
          <div class="proccess_end_span"> </div>
          <div class="proccess_end_span_right"> </div>
        </div>
          <div class="proccess_end_span_p_box">
            <p class="proccess_end_span_p">o</p>
            <p class="proccess_end_span_p">1 000 000₽</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.proccess {
  background: #121212;
}
.proccess_inner {
  padding-left: 202px;
  padding-right: 202px;
  padding-top: 40px;
  padding-bottom: 40px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.proccess_btn {
  border-radius: 16px;
  border: none;
  background: linear-gradient(94.78deg, #df5950 11.19%, #451046 93.72%);
  color: #ffffff;
  padding: 10px 30px;
}
/* .proccess_list {
} */
.proccess_item {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.proccess_item_p {
  font-size: 16px;
}
.proccess_item_p_right {
  margin-left: 20px;
  color: #fff7f7;
  font-size: 16px;
}
.proccess_end_span_wrapper {
  display: flex;
}
/* .proccess_end {
} */
/* .proccess_end_p {
} */
.proccess_end_p_right {
  color: #ffffff;
  margin-left: 20px;
}
.proccess_end_span {
  background: linear-gradient(94.78deg, #df5950 11.19%, #451046 93.72%);
 width: 240px;
  height: 4px;
}
.proccess_end_span_right {
  background: #FFFFFF;
  width: 175px;
  height: 4px;
}
.proccess_end_span_p_box {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
/* .proccess_end_span_p {
} */
</style>