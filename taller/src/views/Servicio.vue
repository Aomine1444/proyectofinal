<template>
  <div class="body">
    <h3>
      <span class="text">Nuestro servicio</span>
    </h3>
    <div class="card-deck">
      <div class="card">
        <h2 class="title-white">Mecanica General</h2>
        <img src="@/assets/mecanica_general.jpg" class="card-img-top" />
        <div class="card-body">
          <p>Reparaciión y Mantenimiento.</p>
          <p>Mantenimientos, revisiones, distribuciones, embragues, culatas, etc.</p>
        </div>
      </div>
      <div class="card">
        <h2 class="title">Revisión</h2>
        <img src="@/assets/aceites.jpg" class="card-img-top" />
        <div class="card-body text-center">
          <p>Aceite, Filtros</p>
          <p>Mano De Obra Incluido</p>
        </div>
      </div>
      <div class="card">
        <h2 class="title">Embragues</h2>
        <img src="@/assets/embraguez.jpg" class="card-img-top" />
        <div class="card-body text-center">
          <p>Cambio y Revisión</p>
        </div>
      </div>
    </div>
    <div class="card-deck">
      <div class="card">
        <h2 class="title-white">Amortiguadores</h2>
        <img src="@/assets/amortiguadores.png" class="card-img-top" />
        <div class="card-body text-center">
          <p>Cambio, Revisión</p>
          <p>Recomendación</p>
        </div>
      </div>
      <div class="card">
        <h2 class="title-white">Frenos</h2>
        <img src="@/assets/frenos.jpg" class="card-img-top" />
        <div class="card-body text-center">
          <p>Cambio, Revisión</p>
          <p>Recomendación</p>
        </div>
      </div>
      <div class="card">
        <h2 class="title-primary">Correas</h2>
        <img src="@/assets/frenos.jpg" class="card-img-top" />
      </div>
    </div>
    <ta />
  </div>
</template>

<script>
import ta from '@/components/ta.vue'

export default {
  components: {
    ta
  }
}
</script>

<style>
.card {
  margin-top: 20px;
}
.card h2{
  text-align: center;
  font-family: "Segoe IU", sans-serif;
  font-style: italic;
  color: #fb3640
}
.body {
  margin: 0px;
  padding: 0px;
}
.body h3{
  text-align: center;
}
.card-deck {
  margin: 15px;
  padding: 10px;
}
.text {
  font-size: 2em;
  font-family: "Latin Modern Roman 10";
  font-style: italic;
}
</style>
