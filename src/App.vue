<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <LoginForm />
    <TodoList />
  </div>
</template>

<script>
import LoginForm from './components/LoginForm.vue'
import TodoList from './components/TodoList.vue'

export default {
  name: 'app',
  components: {
    LoginForm,
    TodoList,
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
