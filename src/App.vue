<template>
  <div id="app">
    <v-header></v-header>
    <div class="tab">
      I am tab.
    </div>
    <div class="content">
      I am content.
    </div>
  </div>
</template>
<script>
  import header from './components/header/header.vue';
  export default {
      'v-header': header
  };
</script>
<style>
</style>
