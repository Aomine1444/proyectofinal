<template>
  <div class="body">
    <h3>
      <span class="text">Nuestro servicio</span>
    </h3>
    <div class="card-deck">
      <div class="card">
        <h2 class="title-white">Mecanica General</h2>
        <img src="@/assets/logo.png" class="card-img-top" />
        <div class="card-body">
          <p>Reparaciión y Mantenimiento.</p>
          <p>Mantenimientos, revisiones, distribuciones, embragues, culatas, etc.</p>
        </div>
      </div>
      <div class="card">
        <h2 class="title">Revicion</h2>
        <img src="@/assets/logo.png" class="card-img-top" />
        <div class="card-body">
          <p>Aceite y filtros</p>
        </div>
      </div>
      <div class="card">
        <h2 class="title">Embragues</h2>
        <img src="@/assets/logo.png" class="card-img-top" />
      </div>
    </div>
    <div class="card-deck">
      <div class="card">
        <h2 class="title-white">Amortiguadores</h2>
        <img src="@/assets/logo.png" class="card-img-top" />
      </div>
      <div class="card">
        <h2 class="title-white">Frenos</h2>
        <img src="@/assets/logo.png" class="card-img-top" />
      </div>
      <div class="card">
        <h2 class="title-primary">Card title</h2>
        <img src="@/assets/logo.png" class="card-img-top" />
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
  background: #edf7fa;
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
