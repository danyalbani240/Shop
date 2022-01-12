<template>
  <div
    class="select-category mx-auto rounded-3xl mt-20 flex items-center justify-between"
    dir="rtl"
  >
    <div class="select flex">
      <p class="text-black text-lg">انتخاب دسته بندی</p>
      <BaseSelect style="margin-right:18px;" :options="['شیرینی']" />    
    </div>
    <BaseSearch placeholder="جستجو" style="margin-left:13px;" />
  </div>
</template>

<script>

export default {}
</script>

<style>
.select-category {
  width: 1180px;
  background-color: #e5e5e5;
  box-shadow: 0px 24px 50px rgba(0, 0, 0, 0.1);
  height: 60px;
}
.select {
  font-size: 24px;
  line-height: 24px;
}
.select p {
    margin-right: 22px;
}
.search {
    border-radius: 24px;
    
}
</style>
