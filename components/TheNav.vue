<template>
  <div class="nav-container">
    <nav class="nav  mx-auto flex flex-row-reverse items-center">
      <img src="../assets/images/logo.svg"  alt="logo" class="logo cursor-pointer" />
      <div class="nav-links flex justify-between byekan" dir="rtl">
        <a href="#" class="nav-link active">صفحه اصلی</a
        ><a href="#" class="nav-link">اطراف من</a
        ><a href="#" class="nav-link">همگردی</a
        ><a href="#" class="nav-link">همبودشو</a
        ><a href="#" class="nav-link">ژورنال</a
        ><a href="#" class="nav-link">کسب و کارها</a>
      </div>
      <div class="flex flex-row-reverse">
          <div class="cart flex items-center byekan text-base cursor-pointer" dir="rtl">
              <img src="../assets/images/cart.svg" alt="cart">
              <p class="text-black mr-1">کارت</p>
          </div>
          <div class="profile mr-8 flex items-center byekan text-base cursor-pointer" dir="rtl">
                <img src="../assets/images/profile.svg" alt="cart">
              <p class="text-black mr-2.5">صفحه کاربری  </p>
          </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {}
</script>

<style lang="css" scoped>
.nav-container {
  width: 100%;
  background-color: #f2f2f2;
}
.logo {
  width: 138px;
  height: 43px;
  animation: Slide_Right 2s forwards;
}
.nav {
  width: 1180px;
  height: 95px;
}
.nav-links {
  
  font-size: 18px;
  width: 581px;
  margin-right: 182px;
}
.nav-link{
  animation: Slide_Up forwards;
}
.nav-link:nth-child(1){
  animation-duration: 1s;
}
.nav-link:nth-child(2){
  animation-duration: 1.2s;

}
.nav-link:nth-child(3){
  animation-duration: 1.5s;

}
.nav-link:nth-child(4){
  animation-duration: 1.7s;

}
.nav-link:nth-child(5){

  animation-duration: 1.8s;
}
.nav-link:nth-child(6){
  animation-duration: 2s;

}



.nav-link.active{
    color: #E47E7A;
}
.cart{
    margin-right: 63px;
    animation: Slide_Down 1s forwards;
}
.profile{
    width: 130px;
    animation: Slide_Down 1.5s forwards;

}
</style>
