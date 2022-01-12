<template>
  <div class="footer flex mt-8" dir="rtl">
    <div class="flex flex-col items-center">
      <img class="filter contrast-0" src="../assets/images/no-colo-logo.svg" alt="" />
      <p class="text-justify text-xs mt-4" dir="rtl">
        رد ام هرابرد نتم ، دریگیم رارق تمسق نیا رد ام هرابرد نتم رارق تمسق نیا
        رد ام هرابرد نتم ، دریگیم رارق تمسق نیا نتم ، دریگیم رارق تمسق نیا رد ام
        هرابرد نتم ، دریگیم نیا رد ام هرابرد نتم ، دریگیم رارق تمسق نیا رد ام
        هرابرد ، دریگیم رارق تمسق
      </p>
    </div>
    <div class="fast-link-container mr-9 ml-5 flex flex-col">
      <a class="active text-center" href="">لینک سریع</a><a href="">لینک سریع</a
      ><a href="">لینک سریع</a><a href="">لینک سریع</a><a href="">لینک سریع</a
      ><a href="">لینک سریع</a>
    </div>
    <div class="fast-link-container ml-5 flex flex-col">
      <a class="active text-center" href="">لینک سریع</a><a href="">لینک سریع</a
      ><a href="">لینک سریع</a><a href="">لینک سریع</a><a href="">لینک سریع</a
      ><a href="">لینک سریع</a>
    </div>
    <div class="fast-link-container flex flex-col">
      <a class="active text-center" href="">لینک سریع</a><a href="">لینک سریع</a
      ><a href="">لینک سریع</a><a href="">لینک سریع</a><a href="">لینک سریع</a
      ><a href="">لینک سریع</a>
    </div>
    <div class="social-media flex flex-col items-center mr-5">
      <p>شبکه های اجتماعی</p>
      <div class="flex items-center mt-3.5">
        <img
          src="../assets/images/instagram.svg"
          alt="../assets/images/instagram.svg"
        /><img class="mx-2" src="../assets/images/instagram.svg" alt="" /><img
          src="../assets/images/instagram.svg"
          alt=""
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.footer {
  width: 100%;
  padding-right: 137px;
  height: 274px;
  padding-top: 46px;
  background: rgba(239, 239, 239, 0.9);
}
.footer > :first-child p {
  width: 257px;
}
.fast-link-container {
  width: 180px;
  height: 157px;
}
.fast-link-container a {
  width: 180px;
  height: 18px;
  margin: 10px 0;
  color: #6d6e71;
}
.fast-link-container a.active {
  color: #e47e7a;
}
.social-media{
    width: 275px;
}
.social-media p{
    color: #e47e7a;
}
</style>
