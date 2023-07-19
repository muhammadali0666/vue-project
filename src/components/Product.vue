<template>
  <div class="product">
    <div class="container">
      <div class="product_inner">
        <h2 class="product_paragraph">Получите профессию прямо сейчас</h2>
        <ul class="product_list">
          <li class="product_item">
            <img src="../assets/nout.png" alt="" class="product_img" />
            <h4 class="product_itemParagraph">
              Только практические навыки в работе
            </h4>
            <p class="product_text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus
              eget velit quisque accumsan amet tortor. Velit, volutpat egestas
              fringilla mi porttitor tempus. Placerat dui.
            </p>
          </li>
          <li class="product_item">
            <img src="../assets/usb.png" alt="" class="product_img" />
            <h4 class="product_itemParagraph">
              Работа на самом современном оборудовании
            </h4>
            <p class="product_text">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Netus
              eget velit quisque accumsan amet tortor. Velit, volutpat egestas
              fringilla mi porttitor tempus. Placerat dui.
            </p>
          </li>
          <li class="product_item">
            <img src="../assets/kabel.png" alt="" class="product_img" />
            <h4 class="product_itemParagraph">
              Сертификация по окончании обучения
            </h4>
            <p class="product_text">
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
.product_inner {
  padding-bottom: 100px;
  padding-left: 202px;
  padding-right: 202px;
  padding-top: 100px;
}
.product_paragraph {
  text-align: center;
  font-size: 48px;
  font-weight: 700;
  color: #ffffff;
  line-height: 67px;
  margin-bottom: 100px;
}
.product_list {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.product_item {
  max-width: 340px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.product_img {
  margin-bottom: 40px;
}
.product_itemParagraph {
  text-align: center;
  color: #ffffff;
  font-size: 24px;
  font-weight: 500;
  line-height: 33px;
}
.product_text {
  text-align: center;
}
</style>