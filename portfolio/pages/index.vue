<template>
  <div>

    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.cdnfonts.com/css/apple-garamond" rel="stylesheet">
    <link href="https://fonts.cdnfonts.com/css/muli" rel="stylesheet"> 
  
      
      <br>
      <br>
      <div class="titulo">
          <h1>Bem-vindo.</h1>
      </div>
      <div class="subtitulo">
          <h2>Estamos em reforma. Cuidado...</h2>
      </div>
  </div>
</template>

<style>

body {
  font-family: 'Muli', sans-serif;
}


body {
  background-image: url('static/mac-wallpaper.jpeg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  margin: 0; 
  padding: 0;
  height: 66vh; 
} 

header ul {
  display: flex;
  list-style: none;
  justify-content: space-between;
  margin-right: 35rem;
  margin-left: 35rem;
}

.link {
  text-decoration: none;
  
}

.titulo {
  text-align: center;
  font-size: 50px;
  font-family: 'Apple Garamond Light', sans-serif;
}

.subtitulo {
  text-align: center;
  font-size: 30px;
  font-family: 'Apple Garamond Light', sans-serif;
}

</style>

<script>
export default {
  name: 'IndexPage'
}
</script>
