<template>
  <div id="app">
    <div id="nav">
      <HelloWorld/>
    </div>
    <router-view/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  components: {
    HelloWorld
  }
}
</script>

<style>

#nav a {
  font-weight: bold;
  color:white;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
