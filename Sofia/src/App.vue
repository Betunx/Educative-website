<template>
  <div class="content">
    <Sidebar />
    <div class="main">
      <Headerblue />
      <User />
      <Navbar />
      <Populares />
      <Secundaria />
    </div>
  </div>
</template>

<script>
import Sidebar from './components/Sidebar.vue'
import Headerblue from './components/Headerblue.vue'
import User from './components/User.vue'
import Navbar from './components/Navbar.vue'
import Populares from './components/Populares.vue'
import Secundaria from './components/Secundaria.vue'

export default {
  name: 'App',
  components: {
    Sidebar,
    Headerblue,
    User,
    Navbar,
    Populares,
    Secundaria,

  },

}
</script>

<style>
#app {
  font-family: 'Times New Roman', Times, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.content {
  display: flex;
  flex-direction: row;
  height: 100vh;

}

.main {
  display: flex;
  flex-direction: column;
  width: 88vw;
}
</style>
