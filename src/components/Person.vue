<template>
  <div class="pessoa">
    <h1>Pessoa:</h1>
    <label for="name">
        Nome | {{name}} <br>
      <input
      type="text"
      v-model="name"
      placeholder="Digite seu nome" />
    </label>
    <br>
    <label for="email">
        E-mail | {{email}} <br>
        <input
        type="text"
        v-model="email"
        placeholder="Digite seu e-mail" />
    </label>
    <br>
      <label for="age">
        Idade | {{age}} <br>
        <input
        type="text"
        v-model="age"
        placeholder="Digite a sua idade" />
    </label>
    <br>
    <label for="bio">
        Biografia | {{bio}} <br>
        <input
        type="text"
        v-model="bio"
        placeholder="Escreva sua biografia" />
    </label>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line
  name: 'Person',
  data() {
    return {
      name: '',
      email: '',
      age: '',
      bio: '',
      isVisible: false,
    };
  },
};
</script>
