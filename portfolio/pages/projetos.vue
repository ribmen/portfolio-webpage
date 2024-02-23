<template>
  <div>
    <h1 class="title">Projetos</h1>
    <p>{{ mensagem }}</p>
    <img src="../static/imac-g3-wallpaper.png" width="300px" height="150px" class="mac-g3">
  </div>
</template>

  <style>

    body {
    background-image: url('static/sem-mac-wallpaper.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    margin: 0; 
    padding: 0;
    height: 66vh; 
    } 

    .title {
      padding: 2rem;
      margin-left: 3rem;
    }

    .mac-g3 {
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
    }

    h1 {
      color: #333;
    }
    p {
      font-size: 16px;
    }
  </style>
    
<script>
export default {
  data() {
    return {
      mensagem: 'Bem-vindo ao Vue.js!'
    };
  }
};
</script>
