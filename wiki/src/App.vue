<template>
  <Header />

  <router-view />
</template>

<script>
import Header from '@/components/Header.vue'; // 导入 Header 组件

export default {
  name: 'App',
  components: {
    Header, // 注册 Header 组件
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>