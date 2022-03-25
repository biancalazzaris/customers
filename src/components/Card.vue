<template>
  <div class="card">
    <h1>Card Componente</h1>
    <!-- <p>{{ name }}</p>
    <p>
      {{ description }}
    </p> -->
    <!-- <p>{{person.name}} </p> -->
  </div>
</template>
<script>
export default {
  name: 'CardProducts',
  props: {
    person: {
      type: Object,
      // required: true,
    },
  },
  data() {
    return {
      // name: 'Notebook',
      // description: 'Corei5, 2,6ghz, 8gb, Tela Widescreen 15,4"',
    };
  },
};
</script>
<style scoped>
.card {
  max-width: 400px;
  height: 200px;
  background-color: #eee;
  border: 1px solid #999;
  color: black;
  padding: 10px;
  margin: 10px;
}

h1 {
  color: blue;
}
</style>
