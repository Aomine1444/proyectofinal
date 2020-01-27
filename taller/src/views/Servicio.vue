<template>
  <div class="body">
    <div class="card-deck">
      <div class="card">
        <img src="@/assets/logo.png" class="card-img-top" />
        <div class="card-body bg-dark">
          <h5 class="card title-white" style="text-align: center">Card title</h5>
          <p
            class="card text-white bg-dark"
          >This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
          <p class="card-text">
            <small class="text-muted">Last updated 3 mins ago</small>
          </p>
        </div>
      </div>
      <div class="card">
        <img src="@/assets/logo.png" class="card-img-top" />
        <div class="card-body bg-dark">
          <h5 class="card title-white" style="text-align: center">Card title</h5>
          <p
            class="card text-white bg-dark"
          >This card has supporting text below as a natural lead-in to additional content.</p>
          <p class="card-text">
            <small class="text-muted">Last updated 3 mins ago</small>
          </p>
        </div>
      </div>
      <div class="card">
        <img src="@/assets/logo.png" class="card-img-top" />
        <div class="card-body bg-dark">
          <h5 class="card title-white" style="text-align: center">Card title</h5>
          <p
            class="card text-white bg-dark"
          >This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
          <p class="card-text">
            <small class="text-muted">Last updated 3 mins ago</small>
          </p>
        </div>
      </div>
    </div>
    <div class="card-deck">
      <div class="card">
        <img src="@/assets/logo.png" class="card-img-top" />
        <div class="card-body bg-dark">
          <h5 class="card title-white" style="text-align: center">Card title</h5>
          <p
            class="card text-white bg-dark"
          >This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
          <p class="card-text">
            <small class="text-muted">Last updated 3 mins ago</small>
          </p>
        </div>
      </div>
      <div class="card">
        <img src="@/assets/logo.png" class="card-img-top" />
        <div class="card-body bg-dark">
          <h5 class="card title-white" style="text-align: center">Card title</h5>
          <p
            class="card text-white bg-dark"
          >This card has supporting text below as a natural lead-in to additional content.</p>
          <p class="card-text">
            <small class="text-muted">Last updated 3 mins ago</small>
          </p>
        </div>
      </div>
      <div class="card">
        <img src="@/assets/logo.png" class="card-img-top" />
        <div class="card-body bg-dark">
          <h5 class="card title-white" style="text-align: center">Card title</h5>
          <p
            class="card text-white bg-dark"
          >This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
          <p class="card-text">
            <small class="text-muted">Last updated 3 mins ago</small>
          </p>
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
.card {
  margin-top: 20px;
}
.body {
  padding-top: 20px;
}
</style>
