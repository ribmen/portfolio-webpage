<template>
  <div>
      <Nuxt/>
  </div>

</template>
  
  <style>
      body {
      font-family: 'Muli', sans-serif;
      background-image: url('static/mac-wallpaper.jpeg');
      background-size: cover;
      background-repeat: no-repeat;
      margin: 0;
    }

    a {
      text-decoration: none;
      color: #000;
    }

    header {
      padding: 0.3rem 0;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1) ;
      width: 100%;
      position: fixed;
      /* background-color: rgba(224, 224, 224, 0.8); */
      backdrop-filter: blur(5px);
    }
    
    header ul {
      display: flex;
      list-style: none;
      justify-content: space-between;
      /* margin-right: 35rem;
      margin-left: 35rem; */
      margin: 0 auto;
      padding: 0 20px;
    }
    
    .link {
      text-decoration: none;
      color: #777;
      transition: color 0.3s ease;
    }

    .link:hover {
      color: #000;
    }
  </style>