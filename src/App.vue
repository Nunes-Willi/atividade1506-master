<script></script>
<template>
  <header class="menu-superior">
      <div class="dropdown">
  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" >
   Menu
  </button>
  <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
    <li><RouterLink to="/">Home</RouterLink></li>
    <li><RouterLink to="/about">Sobre</RouterLink></li>
  </ul>
</div>


<div class="pesquisar">
  <nav class="navbar">
  <div class="container-fluid">
    <form class="d-flex" role="search">
      <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-primary" type="submit">Search</button>
    </form>
  </div>
</nav>
</div>


<div id="bola"></div>
  </header>
  <main><router-view /></main>
  <footer>rodape</footer>
</template>

<style>
@import "@/assets/style.css";
@import "@/assets/style.css";



</style>
