<template>

  <div class="hello">
    <h1 class="mb-4">{{ msg }}</h1>
    <div class="px-2">
      <div class="flex -mx-2">
        <div class="w-1/4 h-12"><router-link v-bind:to="'/forms'"><img src="/static/images/form.svg"></router-link></div>
        <div class="w-1/4 h-12"><img src="/static/images/form.svg"></div>
        <div class="w-1/4 h-12"><img src="/static/images/form.svg"></div>
        <div class="w-1/4 h-12"><img src="/static/images/form.svg"></div>
      </div>
    </div>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to the index page'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
