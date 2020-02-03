<template>
  <div class="bg-dark">
    <div>
      <div class="container">
        <div class="row">
          <div class="col-sm-6">
            <h3 class="text-light m-5" style="font-size: 24px">Mas informacion del Taller</h3>
            <p class="text-light parrafo2">
              Lorem ipsum, dolor sit amet consectetur adipisicing elit.
              Provident optio inventore magnam? Explicabo deserunt alias eos cum, incidunt nulla amet temporibus totam omnis
              harum delectus! Minus nostrum saepe quis corrupti.
            </p>
          </div>
          <div class="col-sm-3">
            <h3 class="text-light m-3" style="font-size: 24px">Redes Sociales</h3>
            <div class="row espaciado">
              <i class="fab fa-facebook imagen"></i>
              <label class="text-light">Siguenos en Facebook</label>
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
              <label class="text-light">direccion,calles y numero de casa</label>
            </div>
            <div class="row2 espaciado2">
              <img src="@/assets/phone.png" class="imagen" />
              <label class="text-light">Numero de Telefonos</label>
            </div>
            <div class="row2 espaciado2">
              <img src="@/assets/correo.png" class="imagen" />
              <label class="text-light">Correo electronico</label>
            </div>
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
