<template>
<nav class="navbar navbar-expand-lg bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="/"><img src="@/assets/logo.png" alt=""></a>
    <button class="navbar-toggler" 
    type="button" 
    data-bs-toggle="collapse" 
    data-bs-target="#navbarSupportedContent" 
    aria-controls="navbarSupportedContent" 
    aria-expanded="false" 
    aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="/">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/player">Animes</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Filmes</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" disabled>Mangas</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Anime" aria-label="Search">
        <button class="botaoPesquisa btn btn-outline" type="submit">Pesquisar</button>
        <a href="/LoginAnimeOn"><i class="avatarAnimeOn fa-solid fa-user-astronaut"></i></a>
      </form>
    </div>
  </div>
</nav>
</template>
<script>
export default {
	
}
</script>
<style scoped>
.navbar-brand img {
  height: 30px;
}
.navbar{
  background: black;
}
.avatarAnimeOn{ 
  margin-left: 10px;
  height: 40px;
  border-radius: 50%;
  color: black;
  transition: 0.4s;
}

.avatarAnimeOn:hover{ 
  color: red;
}
.botaoPesquisa{
  color: red;
  border: 1px solid black;
  transition: .4s;
}

.botaoPesquisa:hover{
  background-color: red;
  color: white;
  border: 1px solid black;
}


</style>