<template>
  <div class=" h-3/5 w-full flex flex-col justify-between" id="bas_page">
    <div class=" flex justify-center mt-8 text-white">
      <span class=" text-4xl">Contacte</span>
    </div>
    <div class=" flex justify-center">
      <span class=" justify-center mx-5 text-gray-500 text-2xl">facebook</span>
      <span class=" justify-center mx-5 text-gray-500 text-2xl">Linkedin</span>
      <span class=" justify-center mx-5 text-gray-500 text-2xl">Gmail</span>
    </div>
    <div class=" w-full flex justify-end pr-7 mb-5">
      <span class=" text-base text-white"> Tel: </span>
      <span class=" text-base text-white"> +261 34 94 591 28 </span>
    </div>
   </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#nav_bar{
  background: #3351bf;
}
#logo{
  font-family: 'Times New Roman', Times, serif;
  color: white;
}
#bas_page{
  background: rgba(0, 0, 0, 0.895);
}
</style>
