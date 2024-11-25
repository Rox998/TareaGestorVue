<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <ul class="navbar-nav">
            <li class="nav-item">
              <router-link to="/">Inicio</router-link> |
            </li>
            <li class="nav-item">
              <router-link to="/addtask">Add Tarea</router-link> |
            </li>
            <li class="nav-item">
              <router-link to="/tasklist">Lista de Tareas</router-link> |
            </li>
            <li class="nav-item">
              <router-link to="/combinedview">Vista remix</router-link>
            </li>
          </ul>

  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
  background-color: black;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
