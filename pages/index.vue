<template>
  <div class="container">
    <top />
    <div>
      <h1 class="title">jososta</h1>
    </div>
    <bottom />
  </div>
</template>

<script>
import top from '../components/nav/top'
import bottom from '../components/nav/bottom'
export default {
  components: {
    top,
    bottom,
  },
}
</script>

<style>
.container {
  text-align: center;
}
</style>
