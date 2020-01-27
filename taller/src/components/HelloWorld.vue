<template>
  <div class="body">
<nav class="navbar navbar-expand-lg navbar-light">
  <a class="navbar-brand" href="/">
        <img src="@/assets/logo.png" width="30" height="30" class="d-inline-block align-top">
        LOGO
      </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
      <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
      <div class="navbar-nav">
        <a class="nav-item nav-link" href="/Nosotros">Nosotros</a>
        <a class="nav-item nav-link" href="/servicio">Servicio</a>
        <a class="nav-item nav-link" href="/contacto">Contacto</a>
      </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
}
</script>

<style>
.navbar {
  background: #202020;
}
.navbar-brand {
  color: #f2f2f2;
}
nav a:hover{
  background: purple;
  transition: 0.5s;
  text-transform: uppercase;
}
.navbar-nav a{
  width: 100px;
  display:block;
  padding: 20px 15px;
  text-decoration:none;
  font-family: Arial;
  color: #f2f2f2;
  text-align: center;
}
</style>
