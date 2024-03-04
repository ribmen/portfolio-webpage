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
        
        <!-- Seu conteúdo HTML aqui -->
        <h1>Sobre mim</h1>
        <p>{{ mensagem }}</p>
      </div>

    </div>


</template>

<script>
export default {
  data() {
    return {
      mensagem: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed at est a elit congue fringilla. Suspendisse sit amet turpis scelerisque, dignissim eros nec, placerat metus. Sed aliquet accumsan massa, sagittis placerat enim accumsan a. Morbi enim lacus, mattis eu mi quis, auctor pharetra metus. Quisque et ex convallis, pretium risus in, accumsan neque. Proin sodales vestibulum nulla eget venenatis. Etiam lectus tortor, placerat id massa in, viverra molestie justo.'
    };
  }
};
</script>

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


h1 {
  color: #333;
  padding: 2rem;
  margin-left: 3rem;
}

p {
  font-family: 'Segoe UI';
  font-weight: 300;
  font-size: 20px;
  padding: 2rem;
  margin-left: 3rem;
}

</style>