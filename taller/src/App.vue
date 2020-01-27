<template>
  <div>
    <div>
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

</style>
