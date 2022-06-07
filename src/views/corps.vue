<template>
  <div class=" h-full ">
    <div class="flex relative">
      <div class=" w-3/5 -mt-32 flex flex-col"  id="texte-1">
        <div class=" pb-10">
          <span class=" text-3xl base_color font-bold">Qui nous sommes?</span>
        </div>
        <div>
            
          <span class=" text-justify ">
            L’Université privée de Madagascar, connue sous le nom de UPRIM, est une université dont le siège social se situe à Antananarivo Madagascar.
            Créée en 2007, elle fait partie des grandes universités reconnues à Madagascar.
            Fondée par RAKOTOVAOARISON Justin, alias Dame de Cœur, elle dispose de 4 sites annexes reparties dans toute l’île et dans l’océan indien, notamment à Majunga, Tamatave, Antsirabe et les îles des Comores.
            UPRIM offre à ces étudiants une éducation et une formation de haute qualité leur permettant d’acquérir, non seulement, de solides compétences professionnelles, mais surtout des aptitudes importantes dans leurs développements personnels, comme la créativité, le dynamisme, la débrouillardise, l'autodidacte et l’ouverture d’esprit.
          </span>

        </div>
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
#texte-1:hover{
  border: solid 4px #002998;
  padding: 20px;
  border-radius: 10px;
}
</style>
