<template>
  <div id="app">
      <h2>How is my rating?</h2>
    <div class="action">
      <star-rating></star-rating>
    </div>
  </div>
</template>

<script>
import StarRating from 'vue-star-rating'

export default {
  name: 'app',
  components: {
    StarRating
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.action {
 display: flex;
    align-items: center;
    justify-content: center;
    }
</style>
