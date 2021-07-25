<template>
  <section class="Estudios">
    <h1>Estudios</h1>
    <ul>
      <li v-for="study in studies" :key="study.study">
        <h2>{{ study.study }}</h2>
        <p>{{ study.description }}</p>
        <p>{{ study.institution }}</p>
      </li>
    </ul>
  </section>
</template>

<script>
export default {
  name: "Estudios",
  props: {},
  data() {
    return {
      studies: [
        {
          study: "En Curso: ",
          description: "Ing. Informática - 5to Semestre",
          institution: "UNIR (Universidad Internacional de la Rioja)",
        },
        {
          study: "Otros estudios: ",
          description: "Ing. Civil - Pregrado",
          institution: "UPB (Universidad Pontificia Bolivariana)",
        },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
