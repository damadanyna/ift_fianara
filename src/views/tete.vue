<template>
  <div class="">
    <div class=" flex justify-between px-3 py-5" id="nav_bar">
      <div class="flex ">
        <div class=" p-1 px-2 border-2 border-white " >
          <span class="  border-2 border-white px-4  text-2xl font-bold" id="logo">IFT</span>
        </div>
        <span class=" text-sm text-white ml-4 font-bold" > Fianarantsoa</span>
      </div>
      <div class=" text-white absoulte">
        <span class=" font-bold mx-2 px-2 cursor-pointer">Accueil</span>
        <span class=" font-bold mx-2 px-2 cursor-pointer">Evenement</span>
        <span class=" font-bold mx-2 px-2 cursor-pointer">Photos</span>
        <span class=" font-bold mx-2 px-2 cursor-pointer">Contacte</span>
      </div>
    </div>
    <svg  class=" " xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#002998" fill-opacity="1" d="M0,128L80,149.3C160,171,320,213,480,197.3C640,181,800,107,960,69.3C1120,32,1280,32,1360,32L1440,32L1440,0L1360,0C1280,0,1120,0,960,0C800,0,640,0,480,0C320,0,160,0,80,0L0,0Z"></path></svg>
    <div class="flex justify-end relative">
      <div class=" -mt-36 mr-11 ">
      <img style="" class=" rounded-lg w-4/5 transform hover:scale-125 " src="../assets/images/those1.jpg" alt="image_diplome">
    </div>
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
  background: #002998;
}
#logo{
  font-family: 'Times New Roman', Times, serif;
  color: white;
}
</style>
