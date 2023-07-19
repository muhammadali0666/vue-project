<template>
  <div class="chart">
    <div class="container">
      <div class="chart_inner">
        <div class="chart_box">
          <div class="chart_box_inner">
            <img
              src="../assets/bistry.png"
              alt="chart"
              class="chart_box_img"
              width="127"
              height="127"
            />
            <p class="chart_box_inner_p">Быстрый старт</p>
          </div>
          <p class="chart_box_p">
            Больше 90% учеников прошли полный курс и смогли собрать свой первый
            компьютер
          </p>
        </div>

        <ul class="chart_list">
          <li class="chart_item">
            <p class="chart_item_p">100%</p>
            <div class="chart_item_box"></div>
            <p class="chart_item_box_text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus
              eget velit quisque accumsan amet tortor. Velit, volutpat egestas
              fringilla mi porttitor tempus. Placerat dui.
            </p>
          </li>
          <li class="chart_item">
            <p class="chart_item_p">50%</p>
            <div class="chart_item_box_two"></div>
            <p class="chart_item_box_text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus
              eget velit quisque accumsan amet tortor. Velit, volutpat egestas
              fringilla mi porttitor tempus. Placerat dui.
            </p>
          </li>
          <li class="chart_item">
            <p class="chart_item_p">75%</p>
            <div class="chart_item_box_three"></div>
            <p class="chart_item_box_text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus
              eget velit quisque accumsan amet tortor. Velit, volutpat egestas
              fringilla mi porttitor tempus. Placerat dui.
            </p>
          </li>
          <li class="chart_item">
            <p class="chart_item_p">Итог</p>
            <div class="chart_item_box_four"></div>
            <p class="chart_item_box_text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus
              eget velit quisque accumsan amet tortor. Velit, volutpat egestas
              fringilla mi porttitor tempus. Placerat dui.
            </p>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
.chart_inner {
  padding-bottom: 100px;
  padding-left: 202px;
  padding-right: 202px;
}
/* .chart_box {
} */
.chart_box_inner {
  display: flex;
  align-items: center;
}
.chart_box_img {
  margin-right: 20px;
}
.chart_box_inner_p {
  font-size: 48px;
  font-weight: 700;
  color: #ffffff;
}
.chart_box_p {
  max-width: 411px;
  font-size: 14px;
  font-weight: 400;
  margin-top: 40px;
}
.chart_list {
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 50px;
}
/* .chart_item {
} */
.chart_item_p {
  font-size: 36px;
  font-weight: 700;
  color: #ffffff;
}
.chart_item_box {
  width: 280px;
  height: 80px;
  background: linear-gradient(94.26deg, #C89AFC 9.51%, #7C6AFA 90.23%);
}
.chart_item_box_two {
  width: 280px;
  height: 60px;
  background: linear-gradient(94.26deg, #C89AFC 9.51%, #7C6AFA 90.23%);
}
.chart_item_box_three {
  width: 280px;
  height: 30px;
  background: linear-gradient(94.26deg, #C89AFC 9.51%, #7C6AFA 90.23%);
}
.chart_item_box_four {
  width: 280px;
  height: 10px;
  background: linear-gradient(94.26deg, #C89AFC 9.51%, #7C6AFA 90.23%);
}
.chart_item_box_text {
  margin-top: 30px;
}
</style>