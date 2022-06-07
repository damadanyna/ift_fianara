<template>
  <div class="h-full w-full relative">
    <accuiel class=" " msg="Welcome to Your Vue.js App"/>
    <corps class=" px-8" />
    <pieds msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import accuiel from './views/tete.vue'
import corps from './views/corps.vue'
import pieds from './views/footer.vue'

export default {
  name: 'App',
  components: {
    accuiel,corps,pieds
  }
}
</script>

<style>

.base_color{
  color:#002998;
}
</style>
