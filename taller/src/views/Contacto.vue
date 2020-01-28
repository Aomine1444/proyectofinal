<template>
  <div>
    <div class="body">
      <h1 class="title">Autoreparaciones Cesar</h1>
      <div class="container-1">
        <h2 class="sub-title">Contacta con Nosotros</h2>
        <p>
          Si necesitas más información sobre nuestra empresa o sobre nuestros servicios,
          ponte en contacto con nosotros, a través del siguiente formulario,
          llamándonos o ven a vernos a nuestras oficinas. Estaremos encantados de atenderte.
        </p>
          <p>Teléfono: 4716903</p>
          <p>Email: Nikodemo23x@outlook.com</p>
          <p>Móvil: 65769812</p>
          <p>Dirección: Quitanilla, Av.Maxfernades</p>
          <p>Horario: 8:00 a 13:00 y 15:00 a 18:30</p>
        <h3 class="sub-title-3">Como llegar</h3>
        <p>
          Por la autopista dirección donosti, salida amorebieta, a 5 km por la nacional n-634,barrio san antonio,
          a mano izquierda (visible desde la carretera). Por la n-634.
        </p>
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
.body h1 {
  text-align: center;
  margin-top: 100px;
  margin-bottom: 100px;
}
* {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  font-family: "Latin Modern Roman 10";
  font-style: italic;
}
.container-1 {
  width: 100%;
  max-width: 1000px;
  margin: auto;
  padding: 60px;
  background: #ffffff;
  margin-top: 60px;
}
.container-1 p {
  font-size: 18px;
  font-weight: 300px;
  margin-top: 15px;
}
</style>
