<template>
  <div class="body bg-dark">
      <div class="container">
        <div class="row">
          <div class="col-sm-6">
            <h3 class="text-light m-5" style="font-size: 24px">Mas informacion del Taller</h3>
            <p class="text-light parrafo2">
               En CESAR´S automotriz, llevamos desde 2015 dándoles el mejor
              servicio profesional y personal. En nuestras instalaciones resolveremos cualquier
              problema mecánico que afecte a su vehículo ajustándonos a plazos acordados y presupuestos.
            </p>
          </div>
          <div class="col-sm-3">
            <h3 class="text-light m-3" style="font-size: 24px">Redes Sociales</h3>
            <div class="row espaciado">
              <i class="fab fa-facebook imagen"></i>
              <label class="text-light"><a href="https://www.facebook.com/cesar.prafo">Siguenos en Facebook</a></label>
            </div>
            <div class="row espaciado">
              <i class="fab fa-instagram imagen"></i>
              <label class="text-light">Siguenos en Instagram</label>
            </div>
            <div class="row espaciado">
              <i class="fab fa-whatsapp-square imagen"></i>
              <label class="text-light">Siguenos en Whatsapp</label>
            </div>
          </div>
          <div class="col-sm-3">
            <h3 class="text-light m-3" style="font-size: 24px">informacion de contacto</h3>
            <div class="row2 espaciado2">
              <img src="@/assets/casa2.png" class="imagen" />
              <label class="text-light">Av. Tercera entre max fernandez y maximiliani kolbe</label>
            </div>
            <div class="row2 espaciado2">
              <img src="@/assets/phone.png" class="imagen" />
              <label class="text-light">+591-60374416</label>
            </div>
            <div class="row2 espaciado2">
              <img src="@/assets/correo.png" class="imagen" />
              <label class="text-light">Cesarprado2012@hotmail.com</label>
            </div>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.row2 label {
  margin-top: 20px;
  margin-left: 20px;
  max-width: 150px;
  color: #c7c7c7;
}
.espaciado {
  margin: 30px;
  color: #c7c7c7;
}
.espaciado2 {
  margin: 10px;
  color: #c7c7c7;
}
.parrafo2 {
  font-size: 14px;
  color: #c7c7c7;
  margin-top: 20px;
}
.imagen {
  width: 30px;
  height: 30px;
}
</style>
