<template>
<div>
<div class="carosel">
  <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active" style="height: 100vh">
      <img src="@/assets/taller3.jpg" class="d-block w-100" alt="...">
       <div class="carousel-caption d-none d-md-block">
      </div>
    </div>
    <div class="carousel-item" style="height: 100vh">
      <img src="@/assets/taller-mecanico1.jpg" class="d-block w-100" alt="...">
       <div class="carousel-caption d-none d-md-block">
      </div>
    </div>
    <div class="carousel-item" style="height: 100vh">
      <img src="@/assets/talle2.jpg" class="d-block w-100" alt="...">
       <div class="carousel-caption d-none d-md-block">
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>
</div>
<Cuerpo/>
  <ta/>
</div>

</template>

<script>
import ta from '@/components/ta.vue'
import Cuerpo from '@/components/Cuerpo.vue'

export default {
  components: {
    Cuerpo,
    ta
  }
}
</script>

<style>

</style>
