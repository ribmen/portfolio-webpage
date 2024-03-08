<template>

  
  <div>

    <div class="overlay"></div>

    <div class="content">
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

      <h1 class="title">Projetos</h1>
      <p class="greeting">{{ mensagem }}</p>

        <div class="scroll-projects">
          <div class="list-projects">
  
            <a href="" class="cards">
              <div class="card1">
                <span><a class="topico" href="https://github.com/ribmen/portfolio-webpage" target="_blank">Portfolio webpage</a></span>
                <p class="text">Me inspirei na interface do iOS para criar uma página limpa e minimalista. Nessa aplicação, usei a tríade básica do desenvolvimento web (HTML, CSS e Javascript) e os conceitos de rotas com Nuxt e Vue.js</p>
                
              </div>
            </a>
  
            <a href="" class="cards">
              <div class="card2">
                <span><a class="topico" href="https://github.com/ribmen/appleWatch" target="_blank">Página do Apple Watch</a></span>
                <p class="text">Um projeto simples e de apelo visual, aqui eu repliquei a página de "vitrine" de pulseiras para o Apple Watch usando os mesmos ícones e aspectos da UI dos sites da Apple.</p>
              </div>
            </a>
  
            <a href="" class="cards">
              <div class="card3">
                <span><a class="topico" href="https://github.com/ribmen/spotify-cloneApplication" target="_blank">Página inicial do Spotify</a></span>
                <p class="text">Aqui foi criada uma réplica da página inicial do aplicativo de streaming Spotify. Alguns detalhes interessantes é que foi desenvolvido um sistema de busca simples baseado numa "API" local. Também foi utilizado React para organizar as partes.</p>
              </div>
            </a>

            <a href="" class="cards">
              <div class="card4">
                <span><a class="topico" href="https://github.com/ribmen/site-Institucional-UFRN" target="_blank">Site institucional da UFRN (fictício)</a></span>
                <p class="text1">Aqui foi criada uma situação onde o DIMAp (UFRN) faz um artigo de apresentação do seu departamento para possíveis ingressantes. Nele implementei uma calculadora de média ponderada para notas do Sisu.</p>
              </div>
            </a>
  
            <a href="" class="cards">
              <div class="card5">
                <span><a class="topico" href="https://github.com/ribmen/spotifyJavaFx" target="_blank">Aplicação de streaming de música</a></span>
                  
                <p class="text1" >Ainda no contexto de streaming de música, isso é uma aplicação em Java de um projeto "spotify-like" de reprodução de músicas localmente com interface gráfica em JavaFX.</p>
              </div>
            </a>
  
            <a href="" class="cards">
              <div class="card6">
                <span><a class="topico" href="https://github.com/ribmen/petShop-website" target="_blank">Site de Petshop (fictício)</a></span>
                <p class="text">Nesse projeto, foi criado um site com design responsivo de um Petshop fictício com integração para contato direto no Whatsapp.</p>
                <img class="imagem" src="../static/card6.png" alt="PetLife pic">
              </div>
            </a>
  
          </div>
        </div>
      


    </div>

  



  </div>
</template>

    <style>
  
      body {
        background-image: url('static/mac-wallpaper.jpeg');
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        margin: 0; 
        padding: 0;
        height: 66vh; 
      } 

      .overlay {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        backdrop-filter: blur(20px); /* Aplica um desfoque ao fundo */
        z-index: 1; /* Coloca a div sobreposta acima do conteúdo da página */
      }

      .content {
        position: relative;
        z-index: 2;
      }
  
      .title {
        padding: 2rem 1rem 2rem 1rem;
        margin-left: 3rem;
      }

      
      .topico {
        text-decoration: none;
        color: #fff;
        padding: 16px;
        position: absolute;
        font-size: 24px;
        font-weight: 700;
      }

      .text {
        font-size: 1.2rem;
        font-family: 'Segoe UI';
        text-align: left;
        text-decoration: none;
        color:#fff;
        position: absolute;
        margin: 4rem 1rem 2rem 1rem;
      }

      .text1 {
        font-size: 1.2rem;
        font-family: 'Segoe UI';
        text-align: left;
        text-decoration: none;
        color:#fff;
        position: absolute;
        margin: 6rem 1rem 2rem 1rem;
      }
      
      .topico:hover {
        text-decoration: underline; 
      }

      .cards {
        position: relative; 
        width: 20rem;
        height: 30rem;
        overflow: hidden;
        border-radius: 30px;
        background-color: rgba(79, 79, 79, 0.493);
        box-shadow: 0 6px 8px rgba(0, 0, 0, 0.3); /* Adiciona uma sombra */
      }

      .imagem {
        height: 12rem;
        width: 20rem;
        position: absolute;
        margin: 18rem 0 0 0;
      }
  
      h1 {
        color: #333;
      }
      .greeting {
        font-size: 20px;
        font-family: 'Segoe UI';
        font-weight: 300;
        padding: 2rem;
        margin-left: 3rem;
      }

      /* .projects-container {
        height: 68vh;
        padding-top: 16px;
        margin: 10px;
        border-radius: 10px;
        background-color: #b5b5b5;
      } */

      .scroll-projects {
        max-height: 81vh;
        margin: 100px;
        overflow: auto;
      }

      .list-projects {
        display: grid;
        justify-items: center;
        grid-template-columns: 2fr 2fr 2fr;
        grid-gap: 2rem;
        gap: 2rem;
        margin-bottom: 2rem;

      }






    </style>
    
    
<script>
export default {
  data() {
    return {
      mensagem: 'Bem-vindo à aba Projetos! Aqui você irá encontrar os projetos nos quais eu tenho trabalhado nos últimos meses. Ultimamente eu tenho focado bastante em Frontend, então prepare-se para encontrar vários projetos de web.'
    };
  }
};
</script>
