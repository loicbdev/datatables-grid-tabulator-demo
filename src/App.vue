<template>
  <div id="app">
    <p>
      Demo : Tabulator
    </p>
    <h2>Sorting using Tabulator</h2>
    <sortable-tabulator></sortable-tabulator>
  </div>
</template>

<script>
import SortableTabulator from './components/SortableTabulator'
export default {
  name: 'app',
  components: {
    SortableTabulator
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
  width: 1000px;
  margin-left: auto;
  margin-right: auto;
}
h2 {
  margin-top: 50px;
}
</style>

<style lang="scss">
@import "~vue-tabulator/dist/scss/bootstrap/tabulator_bootstrap4";
</style>
