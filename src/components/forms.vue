<template>
  <div id="forms">
    <router-link v-bind:to="'/'">Home</router-link>
  </div>
</template>

<script>
export default {
  name: 'forms'
}
</script>
<!-- styling for the component -->
<style>
#forms {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
