<template>
  <div>
  <nav class="navbar navbar-expand-lg navbar-light bg-dark">
      <a class="navbar-brand" href="#"><router-link to="/">Inicio</router-link></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
         <li class="nav-item">
        <a class="nav-link" href="#"><router-link to="/">Inicio</router-link></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"><router-link to="/Nosotros">Nosotros</router-link></a>
      </li>
       <li class="nav-item">
        <a class="nav-link" href="#"><router-link to="/servicio">Servicio</router-link></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#"><router-link to="/contacto">Contacto</router-link></a>
      </li>
    </ul>
  </div>
</nav>
  </div>
</template>

<script>

export default {
}
</script>
