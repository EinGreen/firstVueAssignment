<template>
  <div id="app">
    <!-- Used the components and added them here so they could actually show up on the page -->
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
  </div>
</template>

<script>
// These imports are from the components folder
import PageHeader from "./components/PageHeader.vue";
import PageBody from "./components/PageBody.vue";
import PageFooter from "./components/PageFooter.vue";

export default {
  name: 'App',
  // The components are connected here! Note: vue will be angry if components are not used, which is very useful
  components: {
    PageHeader,
    PageBody,
    PageFooter,
  },
}; 
</script>

<style>
/* defualt styling, did not change */
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
