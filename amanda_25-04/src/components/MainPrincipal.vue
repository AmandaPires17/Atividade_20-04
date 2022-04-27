<script>
import BlocoUm from "@/components/BlocoUm.vue";

export default {
  data() {
    return {
      nomes2: ["Mariana", "Ariane"],
    };
  },
  components: { BlocoUm },
};
</script>
<template>
  <main id="content">
    <BlocoUm id="bloco1" :nomes="['Amanda', 'Antonia']" />

    <BlocoUm id="bloco2" class="alerta" titulo="Alunos" :nomes="nomes2"/>

    <BlocoUm id="bloco3" />

    <BlocoUm id="bloco4" />

    <BlocoUm id="bloco5" />

    <BlocoUm id="bloco6" />

    <BlocoUm id="bloco7"/>

    <BlocoUm id="bloco8"/>
  </main>
</template>
