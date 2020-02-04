<template>
  <div>
    <div>
      <h1 class="title titulo">Autoreparaciones Cesar</h1>
      <div class="container contenedor">
        <div class="contenedor2">
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
        <div class="col-xs-12 col-sm-12 col-md-12">
          <iframe class="iman"
            src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d484.2024633681496!2d-66.10877125188553!3d-17.38127822867462!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e1!3m2!1ses!2sbo!4v1580764653532!5m2!1ses!2sbo"
            width="600"
            height="450"
            frameborder="0"
            style="max-width 100%"
            allowfullscreen
          ></iframe>
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
  text-align: center;
  margin-top: 100px;
  margin-bottom: 100px;
  font-family: "Latin Modern Roman 10";
  font-style: italic;
}
.contenedor {
  width: 100%;
  max-width: 1000px;
  margin: auto;
  padding: 60px;
  background: #ffffff;
  margin-top: 60px;
}
.contenedor2 {
  font-size: 18px;
  font-weight: 300px;
  margin-top: 15px;
  font-family: "Latin Modern Roman 10";
  font-style: italic;
}
.iman{
  width: 100%;
  margin-top: 50px;
  margin-bottom: 50px;
}
</style>
