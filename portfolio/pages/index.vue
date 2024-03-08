<template>
  <div>  
    <header>
        <div style="height: 2rem" >
            <ul>
  
              <nuxt-link to="/">
                <li class="link">HOME</li>
              </nuxt-link>
  
              <nuxt-link to="projetos">
                <li class="link">PROJETOS</li>  
              </nuxt-link>
  
              <nuxt-link to="sobre-mim">
                <li class="link">SOBRE MIM</li>
              </nuxt-link>
  
            </ul>
          </div>
        </header>
           
      <br>
      <h1 class="titulo">Bem-vindo.</h1>

      <h2 class="subtitulo">Estamos em reforma. Cuidado...</h2>

    </div>
</template>

    <style>
       
    body {
      background-image: url('static/mac-wallpaper.jpeg');
      background-size: cover;
      background-repeat: no-repeat;
    } 

    header {
      padding: 0.3rem 0;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1) ;
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
      color: #777;
      transition: color 0.3s ease;
    }

    .link:hover {
      color: #000;
    }
    
    .titulo {
      margin: 2rem 0 0 0;
      text-align: center;
      font-size: 7rem;
      font-family: 'Apple Garamond Light', sans-serif;
    }
    
    .subtitulo {
      margin-left: 0;
      text-align: center;
      font-size: 2.5rem;
      font-family: 'Apple Garamond Light', sans-serif;
    }
    
    </style>

<script>
export default {
  data(){
    return {
      name: 'IndexPage'
    }
  }
  
}
</script>