<template>
  <div id="hello-world-page" class="hello-world-page" />
</template>

<script>
import * as Cesium from 'cesium'
export default {
  name: 'HelloWorld',

  mounted() {
    const viewer = new Cesium.Viewer('hello-world-page')
    console.log(viewer)
  },
}
</script>

<style lang="scss" scoped>
.hello-world-page {
  display: flex;
  width: 100%;
  height: 100%;
  justify-content: center;
}
</style>
