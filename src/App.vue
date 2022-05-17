<template>
<div>

  <h1>APP ROUTER</h1>
<router-view></router-view>
<Click-Counter />
<Hover-Counter />

</div>
</template>

<script>
import ClickCounter from "./components/ClickCounter.vue";
import HoverCounter from "./components/HoverCounter.vue";


export default {
  name: 'App',
  components: {
    ClickCounter,
    HoverCounter
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
