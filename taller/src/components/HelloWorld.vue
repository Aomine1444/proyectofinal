<template>
  <div class="contenedor3">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <a class="navbar-brand" href="/">
        <img src="@/assets/logo.png" width="30" height="30" class="d-inline-block align-top" />
        LOGO
      </a>
      <button
        class="navbar-toggler bg-dark"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
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

.navbar-brand {
  color: #f2f2f2;
}
.navbar a:hover {
  background: #1c54a0;
  transition: 0.5s;
  text-transform: uppercase;
  padding: 16xp 15px;
  overflow: hidden;
  position: relative;
  display: block;
}
.navbar-nav a {
  text-decoration: none;
  font-family: Arial;
  color: #f2f2f2;
  text-align: -webkit-match-parent;
  list-style: none;
  margin-left: 200px;
}
.contenedor3{
  width: 100%;
}
</style>
