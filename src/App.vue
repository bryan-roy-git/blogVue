<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <div class="container">
  <HeaderComponent></HeaderComponent>
  <PostListComponent></PostListComponent>
  <FooterComponent></FooterComponent>
  </div>

</template>

<script>
import FooterComponent from './components/Partials/FooterComponent.vue'
import HeaderComponent from './components/Partials/HeaderComponent.vue'
import PostListComponent from './components/PostListComponent.vue'


export default {
  name: 'App',
  components: {
    HeaderComponent,
    FooterComponent,
    PostListComponent

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
  /* margin-top: 60px; */
}
</style>
