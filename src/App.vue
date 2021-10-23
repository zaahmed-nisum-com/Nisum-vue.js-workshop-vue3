<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Interpolation/>
  <Directive/>
  <LifeCycle/>
</template>

<script>
import Interpolation from './class_1/Interpolation.vue'
import Directive from './class_1/Directive.vue'
import LifeCycle from './class_1/LifeCycle.vue'

export default {
  name: 'App',
  components: {
    Interpolation,
    Directive,
    LifeCycle
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
