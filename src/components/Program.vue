<template>
  <div class="program">
    <div class="container">
      <div class="program_inner">
        <img
          src="../assets/icon-heading-1.png"
          alt="icon"
          class="program_img"
          width="127"
          height="127"
        />
        <h2 class="program_paaragraph">Программа обучения</h2>
        <p class="prgram_p">
          Больше 90% учеников прошли полный курс и смогли собрать свой первый
          компьютер
        </p>
        <div class="program_box">
          <div class="program_box_left">
            <div class="program_box_inner">
              <div class="program_box_inner_in">
                <p class="program_box_inner_in_p">Неделя №1</p>
                <p class="program_box_inner_in_h4">
                  Неделя №1 Красивая часть курса, которая помогает в успехе
                </p>
              </div>
              <div class="program_box_inner_in_span"> </div>
            </div>
            <div class="program_box_inner">
              <div class="program_box_inner_in">
                <p class="program_box_inner_in_p">Неделя №3</p>
                <p class="program_box_inner_in_h4">
                  Красивая часть курса, которая помогает в успехе
                </p>
              </div>
              <div class="program_box_inner_in_span"> </div>
            </div>
            <div class="program_box_inner">
              <div class="program_box_inner_in">
                <p class="program_box_inner_in_p">Неделя №5</p>
                <p class="program_box_inner_in_h4">
                  Красивая часть курса, которая помогает в успехе
                </p>
              </div>
              <div class="program_box_inner_in_span"> </div>
            </div>
            <div class="program_box_inner">
              <div class="program_box_inner_in">
                <p class="program_box_inner_in_p">Неделя №7</p>
                <p class="program_box_inner_in_h4">
                  Красивая часть курса, которая помогает в успехе
                </p>
              </div>
              <div class="program_box_inner_in_span"> </div>
            </div>
          </div>
          <div class="program_box_middle"></div>
          <div class="program_box_right">
            <div class="program_box_inner_right">
              <div class="program_box_inner_in_span_right"> </div>
              <div class="program_box_inner_in_right">
                <p class="program_box_inner_in_p_right">Неделя №1</p>
                <p class="program_box_inner_in_h4_right">
                  Неделя №1 Красивая часть курса, которая помогает в успехе
                </p>
              </div>
            </div>
            <div class="program_box_inner_right">
              <div class="program_box_inner_in_span_right"> </div>
              <div class="program_box_inner_in_right">
                <p class="program_box_inner_in_p_right">Неделя №1</p>
                <p class="program_box_inner_in_h4_right">
                  Неделя №1 Красивая часть курса, которая помогает в успехе
                </p>
              </div>
            </div>
            <div class="program_box_inner_right">
              <div class="program_box_inner_in_span_right"> </div>
              <div class="program_box_inner_in_right">
                <p class="program_box_inner_in_p_right">Неделя №1</p>
                <p class="program_box_inner_in_h4_right">
                  Неделя №1 Красивая часть курса, которая помогает в успехе
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.program_inner {
  padding-left: 410px;
  padding-right: 410px;
  padding-top: 100px;
  padding-bottom: 100px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
/* .program_img {
} */
.program_paaragraph {
  font-size: 38px;
  font-weight: 700;
  margin-bottom: 20px;
  color: #ffffff;
}
.prgram_p {
  margin-bottom: 50px;
  text-align: center;
  width: 411px;
}
.program_box {
  display: flex;
  align-items: center;
}
.program_box_left {
  display: flex;
  flex-direction: column;
}
.program_box_inner {
  display: flex;

  justify-content: space-between;
}
.program_box_inner_in {
  display: flex;
  flex-direction: column;
  align-items: end;
}
.program_box_inner_in_p {
  font-size: 14px;
  margin-bottom: 20px;
}
.program_box_inner_in_h4 {
  font-size: 16px;
  color: #ffffff;
  margin-bottom: 70px;
  text-align: center;
}
.program_box_inner_in_span {
  width: 40px;
  height: 1px;
  background-color: #736b6b;
  margin-top: 55px;
}
.program_box_middle {
  background: linear-gradient(94.26deg, #C89AFC 9.51%, #7C6AFA 90.23%);
  width: 6px;
  height: 667px;
}
.program_box_right {
display: flex;
flex-direction: column;

}
.program_box_inner_right {
display: flex;
}
.program_box_inner_in_right {
  display: flex;
  flex-direction: column;
  align-items: start;
  margin-left: 30px;
}
.program_box_inner_in_p_right {
  font-size: 14px;
  margin-bottom: 20px;
}
.program_box_inner_in_h4_right {
  color: #ffffff;
  margin-bottom: 70px;
}
.program_box_inner_in_span_right {
  width: 40px;
  height: 1px;
  background-color: #736b6b;
  margin-top: 55px;
}

</style>