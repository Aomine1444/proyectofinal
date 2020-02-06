<template>
  <div class="body">
    <div class="container">
      <h1 class="titulo">Quienes Somos</h1>
      <div class="row">
        <div class="col-xs-12 col-sm-6 col-md-6" style="max-width: 100%">
          <img src="@/assets/índice.jpg" class="img-tr" />
        </div>
        <div class="col-xs-12 col-sm-6 col-md-6">
          <article class="parrafo">
            <p>
              En CESAR´S automotriz, llevamos desde 2015 dándoles el mejor
              servicio profesional y personal. En nuestras instalaciones resolveremos cualquier
              problema mecánico que afecte a su vehículo ajustándonos a plazos acordados y presupuestos.
            </p>
            <p>
              Disponemos de nuevas y preparadas instalaciones para efectuar reparaciones
              de manera más rápida, eficaz y darle el mejor servicio.
            </p>
            <p>
              CESAR´S automotriz, forma parte de la red de Taller XXI. Nuestras ventajas de formar
              parte de esta red es que disponemos de su imagen, tecnología, marketing, equipamiento, información y experiencia.
            </p>
          </article>
        </div>
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
.titulo {
  font-size: 50px;
  margin-top: 50px;
  margin-bottom: 10px;
  text-align: center;
  box-sizing: border-box;
  font-family: "Latin Modern Roman 10";
  font-style: italic;
}
.img-tr {
  width: 100%;
  height: 550px;
  margin: auto;
  margin-top: 50px;
  margin-bottom: 50px;
  padding: 10px;
  display: block;
}
.parrafo {
  margin: 50px;
  font-family: "Latin Modern Roman 10";
  font-style: italic;
  padding: 15px;
}
.body {
  margin: 0px;
  padding: 0px;
}
</style>
