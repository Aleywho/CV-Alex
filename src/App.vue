<template>
  <MenuVue/>
  <HomeVue/>
</template>

<script>
import HomeVue from './components/Home.vue'
import MenuVue from './components/Menu.vue'

export default {
  name: 'App',
  components: {
    HomeVue,
    MenuVue
    
  }
}
</script>

<style>
:root{
  --accent-color:rgb(82, 84, 231);
}

body{
  background-color: rgb(19, 18, 18);
  padding: 0px;
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align:left;
  color: #969696;
  margin-top: 60px;
}

</style>
