<template>
  <div>
    <TheNav />
    <div class="category-container mx-auto">
      <p class="text-black text-center">دسته بندی محصولات</p>
      <div class="flex category mx-auto justify-between">
        <div class="category-item h-full bg-white flex flex-col items-center">
          <img class="mt-8" src="../assets/images/cake.svg" alt="cake">
          <p class="text-center mt-6">کیک</p>
        </div>
        <div class="category-item h-full bg-white flex flex-col items-center">
          <img class="mt-8" src="../assets/images/bread.svg" alt="cake">
          <p class="text-center mt-6">نان</p>

        </div>
        <div class="category-item h-full bg-white flex flex-col items-center">
          <img class="mt-8" src="../assets/images/cookies.svg" alt="cake">
          <p class="text-center mt-6">ساندویچ</p>

        </div>
        <div class="category-item h-full bg-white flex flex-col items-center">
          <img class="mt-8" src="../assets/images/cake.svg" alt="cake">
          <p class="text-center mt-6">شیرینی</p>

        </div>
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
.category-item p{
  font-size: 24px;
line-height: 24px;

}
</style>
