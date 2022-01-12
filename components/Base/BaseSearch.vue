<template>
  <div class="bg-white custom-search relative rounded-3xl">
      <input :placeholder="placeholder" class="rounded-3xl" type="text">
      <img class="absolute search-icon" src="../../assets/images/search.svg" />
          
      
  </div>
</template>

<script>
export default {
    props:{
        placeholder:{
            required:true,
            type:String
        }
    }
}
</script>

<style>
.custom-search {
  width: 228px;
  height: 35px;
  background-color: #FFFFFF;

}
.custom-search input{
  width: 100%;
  height: 100%;
  background-color: #FFFFFF;

}
.custom-search input::placeholder{
 padding-right: 21px;
 color: #313039;
}
.search-icon{
    left: 15px;
    top: 50%;
    transform: translateY(-50%);
}
</style>
