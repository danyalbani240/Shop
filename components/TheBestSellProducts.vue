<template>
  <div class="best-products-container mx-auto mt-20">

      <p class="text-3xl text-center text-black">خرید محصولات پر فروش</p>
      <div class="flex">
        <img style="margin-right:14px;" class="cursor-pointer" src="../assets/images/leftarrow.svg" alt=""><img src="../assets/images/rightarrow.svg" alt="">
      </div>
    <div class="best-products flex items-end justify-between">
      <BaseItem />
      <BaseItem :discount="2" />
      <BaseItem />
      <BaseItem />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.best-products-container {
  width: 1180px;
  height: 327px;    
}
.best-products{
  
  width: 100%;
  height: 327px;
  margin-top: 17px;
}
</style>
