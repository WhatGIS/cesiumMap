

<template>
  <div id="cesiumContainer"></div>
</template>
<script setup lang="ts">
import {onMounted, ref} from 'vue'
import * as Cesium from 'cesium'

onMounted(()=>{
  let viewer = new Cesium.Viewer("cesiumContainer")
})
</script>
<style scoped>
#cesiumContainer {
  width: 100%;
  height: 100%;
  overflow: hidden;
}
.read-the-docs {
  color: #888;
}
</style>
