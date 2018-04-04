<template>
  <div id="actions">
    <router-link v-bind:to="'/'">Home</router-link>
    <h1 class="mb-4">{{ msg }}</h1>

    <div class="pt-8 pb-8">
    Visually differentiate between primary and secondary actions.
      <div class="pt-4 mx-8 sm:flex sm:justify-center">
        <div class="bg-#fafafa h-48 w-1/3 p-8 shadow">
          Are you sure you want to continue with your primary action?
          <div class="pt-8">
            <img src="/static/images/action1.svg">
          </div>
        </div>
      </div>
    </div>

    <div class="pt-8 pb-8">
    Visually differentiate between primary and secondary actions.
      <div class="pt-4 mx-8 sm:flex sm:justify-center">
        <div class="bg-#fafafa h-48 w-1/3 p-8 shadow">
          Are you sure you want to continue with your primary action?
          <div class="pt-8">
            <img src="/static/images/action1.svg">
          </div>
        </div>
      </div>
    </div>

    <div class="pt-8 pb-8">
    Visually differentiate between primary and secondary actions.
      <div class="pt-4 mx-8 sm:flex sm:justify-center">
        <div class="bg-#fafafa h-48 w-1/3 p-8 shadow">
          Are you sure you want to continue with your primary action?
          <div class="pt-8">
            <img src="/static/images/action1.svg">
          </div>
        </div>
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
