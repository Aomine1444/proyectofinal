<template>
  <div class="Body6">
    <div class="main-container">
      <h1>Quienes Somos</h1>
      <div class="all-row">
        <div class="clearfix visible-sm-block"></div>
        <aside class="col-xs-12 col-sm-6 col-md-3 col-md-offset-4">
        <img src="@/assets/sanpedro.jpg" class="img-tr rounded mx-auto d-block"/>
        </aside>
        <article class="col-xs-12 col-sm-6 col-md-9 text-center">
          <p>
        En auto-reparaciones San Antonio, llevamos desde 1974 dándoles el mejor
        servicio profesional y personal. En nuestras instalaciones resolveremos cualquier
        problema mecánico que afecte a su vehículo ajustándonos a plazos acordados y presupuestos.
      </p>
      <p>
        Disponemos de nuevas y preparadas instalaciones para efectuar reparaciones
        de manera más rápida, eficaz y darle el mejor servicio.
      </p>
      <p>
        Auto-reparaciones San Antonio forma parte de la red de Taller XXI. Nuestras ventajas de formar
        parte de esta red es que disponemos de su imagen, tecnología, marketing, equipamiento, información y experiencia.
      </p>
        </article>
      </div>
    </div>
    <ta/>
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
h1{
  font-size: 50px;
  margin-bottom: 70px;
  text-align: center;
  box-sizing: border-box;
  font-family: "Latin Modern Roman 10";
  font-style: italic;
}
.img-tr{
  width: 530px;
  height: 565px;
  float: left;
  margin-right: 60px;
  padding-bottom: 60px;
}
.main-container p{
  margin-top: 15px;
  font-family: "Latin Modern Roman 10";
  font-style: italic;
  margin-left: 40px;
  padding-bottom: 60px;
}
</style>
