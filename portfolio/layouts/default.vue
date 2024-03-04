<template>
  <div>
 
    <!-- <header>
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
      </header> -->
      <Nuxt/>
  </div>

</template>
  
  <style>
      body {
      font-family: 'Muli', sans-serif;
    }

      header {
        background-color: #fff;
        
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
  </style>