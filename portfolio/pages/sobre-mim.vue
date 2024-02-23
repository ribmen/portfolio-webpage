<template>
  <div>
    <!-- Seu conteúdo HTML aqui -->
    <h1>Sobre mim</h1>
    <p>{{ mensagem }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mensagem: 'Bem-vindo ao Vue.js!'
    };
  }
};
</script>

<style>
h1 {
  color: #333;
}
p {
  font-size: 16px;
}
</style>