<template>
  <!-- App principale in cui importiamo i vari "pezzi" -->
  <div>
    <!-- "Title" creato da me ed importato -->
    <Title />

    <!-- "Hero" creato da me ed importato -->
    <Hero />
  </div>
</template>
  
<script>
//| Momento in cui importo i file per poterli utilizzare
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";
export default {
  components: {
    Title,
    Hero,
  },
};
</script>

<style>
/* Eventuale stile per la pagina principale
Non per forza necessario, visto e considerato che 
Lavoriamo a "pezzi" */
</style>
