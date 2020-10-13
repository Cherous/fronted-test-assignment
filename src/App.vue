<template>
  <div id="app">
    <test-task/>
  </div>
</template>

<script>
import TestTask from './components/TestTask'

export default {
  name: 'App',
  components: {
    TestTask
  }
}
</script>

<style lang="scss">
  body {
    margin: 0;
  }

#app {
  *,
  *:before,
  *:after {
    box-sizing: border-box;
  }
}
</style>
