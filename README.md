# todo-vue-cli

## Project setup
```bash
$ npm install
```

### Compiles and hot-reloads for development
```bash
$ npm run serve
```

### Compiles and minifies for production
```bash
$ npm run build
```

### Lints and fixes files
```bash
$ npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Todo app with Vue

```vue
<template>
  <div class="todo-list">

    ...

  </div>
</template>

<script>
export default {
  props: [],

  data: function() {
    return {}
  },

  methods: {
    addTodo: function() {}
    },

    removeTodo: function(todoID) {}
  }
}
</script>

<style>
  .todo-list {
    display: inline-block;
    width: 33%;
  }
</style>
```