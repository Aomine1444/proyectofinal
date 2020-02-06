<template>
  <div class="body">
        <nav class="navbar navbar-expand-md navbar-light bg-dark">
          <a class="navbar-brand" href="/">
            <img srcset="@/assets/logo2.jpg 3x @/assets/logo2.jpg 3x @/assets/LOGO SOLO 2.png 1x" width="170" height="100" class="d-inline-block align-top" />
          </a>
          <button
            class="navbar-toggler bg-light"
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
              <a class="nav-item nav-link text-light" href="/Nosotros">Nosotros</a>
              <a class="nav-item nav-link text-light" href="/servicio">Servicio</a>
              <a class="nav-item nav-link text-light" href="/contacto">Contacto</a>
            </div>
          </div>
        </nav>
  </div>
</template>

<script>
export default {}
</script>

<style>
.navbar-brand {
  color: #f2f2f2;
}
.navbar a:hover {
  background: #1c54a0;
  transition: 0.5s;
  text-transform: uppercase;
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
  margin-left: 50px;
}
.Cont {
  max-width: 100%;
  height: 60px;
  margin: 0px;
  padding: 0px;
}
.color5 {
  background: black;
}
.body {
  margin: 0px;
  padding: 0px;
}
</style>
