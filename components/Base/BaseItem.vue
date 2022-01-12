<template>
  <div class="item rounded-3xl flex flex-col items-center relative">
    <div class="absolute discount top-0 left-0 rounded-full flex items-center justify-center text-center" v-if="discount">
      <p dir="rtl">تخفیف 20%</p>
    </div>
    <img
      src="../../assets/images/thumbnail-demo.svg"
      class="thumbnail rounded-3xl"
      alt="thumbnail"
    />
    <p class="title-code" dir="rtl">
      کیک شکلاتی -
      <span class="code">#65232</span>
    </p>
    <span class="item-category">دسته بندی:کیک</span>
    <div class="buy-btn flex rounded-3xl cursor-pointer" dir="rtl">
      <span class="flex px-3 items-center">
        <img
          class="add-circle"
          src="../../assets/images/add-circle.svg"
          alt=""
        />
        <span style="color: white; margin-right: 5px" class="text-lg"
          >خرید</span
        >
      </span>
      <span class="flex items-center justify-end pl-4 text-left flex-1">
        25.000.000
      </span>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    discount: {
      type: Number,
      required: false,
    },
  },
}
</script>

<style>
.item {
  background: #ffffff;
  box-shadow: 0px 24px 50px rgba(0, 0, 0, 0.1);
  width: 280px;
  height: 280px;
  transform: translateY(-15.5px);
}
.thumbnail {
  width: 174px;
  height: 174px;
  margin-top: 31px;
}
.title-code {
  margin-top: 14px;
  font-size: 18px;
  line-height: 18px;
}
.code {
  color: #e47e7a;
}
.item-category {
  margin: 0;
  font-size: 12px;
  line-height: 12px;
  color: #b5b5b5;
}
.buy-btn {
  width: 228px;
  height: 35px;
  overflow: hidden;
  background: #e47e7a;
  color: white;
  transform: translateY(50%);
}
.buy-btn > :nth-child(1) {
  background: rgba(0, 0, 0, 0.2);
  width: 82px;
}
.add-circle {
  width: 14px;
  height: 14px;
}
.discount{
  width: 60px;
  height: 60px;
  color: white;
  background-color: #E47E7A;
  transform: translate(-16px,-50%);
}
.discount p{
  width: 44px;
}
</style>
