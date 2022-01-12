<template>
  <div class="nav-container">
    <nav class="nav mx-auto flex flex-row-reverse items-center">
      <img src="../assets/images/logo.svg" alt="logo" class="logo" />
      <div class="nav-links flex justify-between" dir="rtl">
        <a href="#" class="nav-link">صفحه اصلی</a
        ><a href="#" class="nav-link">اطراف من</a
        ><a href="#" class="nav-link">همگردی</a
        ><a href="#" class="nav-link">همبودشو</a
        ><a href="#" class="nav-link">ژورنال</a
        ><a href="#" class="nav-link">کسب و کارها</a>
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
}
.nav {
  width: 1180px;
  height: 95px;
}
.nav-links {
  line-height: 18px;
  font-size: 18px;
  width: 581px;
  margin-right: 182px;
}
</style>
