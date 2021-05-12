<template>
  <Users />
</template>

<script>
import Users from './components/Users.vue'

export default {
  name: 'App',

  components: {
    Users,
  },

  setup () {
    return {}
  },
}
</script>

<style>
body {
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  font-size: 24px;
  text-align: center;
  color: #2c3e50;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100vw;
  height: 100vh;
}

h2 {
  margin: 10px 0;
  line-height :1;
}

button {
  display: inline-block;
  padding: 10px 30px;
  background: #34495E;
  border: 0;
  border-radius: 5px;
  color: white;
  font-size: 20px;
  margin: 10px 0;
  cursor: pointer;
}

em {
  display: block;
  padding: 10px;
  border: 1px solid #f53f3f;
  background: #ffe0e0;
  color: #da2828;
  margin: 10px 0;
}
</style>
