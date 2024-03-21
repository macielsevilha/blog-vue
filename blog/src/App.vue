<template>
 <div class="app">
  <header-component />
  <content-component />
  <footer-component />
 </div>
  
</template>

<script>
import HeaderComponent from './components/Layout/HeaderComponent.vue';
import ContentComponent from './components/Layout/ContentComponent.vue';
import FooterComponent from './components/Layout/FooterComponent.vue';

export default {
  name: 'App',
  components: { HeaderComponent, ContentComponent, FooterComponent }
  
}
</script>

<style>

.app {
  display: grid;
  grid-auto-columns: 1fr 1fr 1fr;
  grid-auto-rows: "header";
}

</style>