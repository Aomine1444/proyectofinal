<template>
  <div class="Body">
    <div class="container-all">
      <h1>Quienes Somos</h1>
      <img src="@/assets/sanpedro.jpg" />
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
*{
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  font-family: "Latin Modern Roman 10";
  font-style: italic;
}
h1{
  font-size: 50px;
  margin-bottom: 70px;
  text-align: center;
}
.container-all{
  width: 100%;
  max-width: 1000px;
  margin: auto;
  padding: 60px;
  background: #ffffff;
  margin-top: 10px;
}
.container-all img{
  width: 530px;
  height: 465px;
  float: left;
  margin-right: 30px;
  padding-bottom: 60px;
}
.container-all p{
  font-size: 18px;
  font-weight: 300px;
  margin-top: 15px;
}
</style>
