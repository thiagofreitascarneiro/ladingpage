<template>
  <div id="app">
    <BlogHome/>
    <BlogPackage/>
    <BlogVideo/>
    <BlogPrice/>
    <BlogClient/>
    <BlogEducation/>
  </div>
</template>

<script>
import BlogHome from './components/BlogHome.vue'
import BlogPackage from './components/BlogPackage.vue';
import BlogVideo from './components/BlogVideo.vue';
import BlogPrice from './components/BlogPrice.vue';
import BlogClient from './components/BlogClient.vue';
import BlogEducation from './components/BlogEducation.vue';

export default {
  name: 'App',
  components: {
    BlogHome,
    BlogPackage,
    BlogVideo,
    BlogPrice,
    BlogClient,
    BlogEducation
  }
}
</script>

<style lang="scss">
@import "../src/assets/scss/main.scss";

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
