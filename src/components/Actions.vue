<template>
  <div id="actions">
    <router-link v-bind:to="'/'">Home</router-link>
    <h1 class="mb-4">{{ msg }}</h1>

    <div class="container mx-auto">
      <div class="bg-#fafafa h-48 w-1/3 p-8 shadow">
        <img src="/static/images/action1.svg">
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'actions'
}
</script>
<!-- styling for the component -->
<style>
#actions {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
