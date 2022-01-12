<template>
  <div>
    <TheNav />
    <div class="category-container mx-auto">
      <p class="text-black text-center">دسته بندی محصولات</p>
      <div class="flex category mx-auto justify-between">
        <div class="category-item h-full bg-white flex flex-col items-center">
          <img class="mt-8" src="../assets/images/cake.svg" alt="cake" />
          <p class="text-center mt-6">کیک</p>
        </div>
        <div class="category-item h-full bg-white flex flex-col items-center">
          <img class="mt-8" src="../assets/images/bread.svg" alt="cake" />
          <p class="text-center mt-6">نان</p>
        </div>
        <div class="category-item h-full bg-white flex flex-col items-center">
          <img class="mt-8" src="../assets/images/cookies.svg" alt="cake" />
          <p class="text-center mt-6">ساندویچ</p>
        </div>
        <div class="category-item h-full bg-white flex flex-col items-center">
          <img class="mt-8" src="../assets/images/cake.svg" alt="cake" />
          <p class="text-center mt-6">شیرینی</p>
        </div>
      </div>
    </div>
    <TheSelectCategory />
    <TheBestSellProducts />
    <div class="big-banner rounded-3xl mx-auto byekan" dir="rtl">
      <div class="text-right">
        <p>بهترین محصولات کیک و شیرینی را در فروشگاه ما دنبال کنید</p>
        <button class="buy-now flex items-center justify-center text-center byekan text-lg">همین حالا خرید کنید</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
<style scoped>
.category-container {
  margin-top: 43px;
  width: 872px;
}
.category-container p {
  font-size: 32px;
  line-height: 32px;
}
.category {
  width: 872px;
  margin-top: 26px;
  height: 160px;
}
.category-item {
  width: 194px;
  box-shadow: 0px 24px 50px rgba(0, 0, 0, 0.1);
  border-radius: 24px;
  cursor: pointer;
}
.category-item p {
  font-size: 24px;
  line-height: 24px;
}
.big-banner {
  margin-top: 105px;
  width: 1180px;
  height: 533px;
  padding-top:195px;
  background-image: url(../assets/images/big-banner.svg);}

.big-banner p{
  width: 405px;
height: 86px;
margin-right: 89px;
font-size: 32px;
line-height: 32px;
color: white;

}
.big-banner button{
  margin-top: 23px;
  width: 228px;
height: 35px;
background: #E47E7A;
border-radius: 24px;
margin-right: 89px;
color: white;
}
</style>
