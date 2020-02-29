<template>
    <div id="wrapper" class="clearfix">
        <canvas-slider
                title="organomad"
                subtitle="coming soon" />
    </div>
</template>

<script>
import CanvasSlider from './components/CanvasSlider.vue'

export default {
  name: 'App',
  components: {
    CanvasSlider
  }
}
</script>

<style>
#wrapper {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  opacity: 1 !important;
}
</style>
