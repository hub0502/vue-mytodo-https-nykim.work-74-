<template>
  <div id="app">
    <todo-header />
    <todo-title />
    <todo-input />
    <todo-controller />
    <todo-list />
    <todo-footer />
  </div>
</template>

<script>
import TodoHeader from './components/TodoHeader.vue'
import TodoTitle from './components/TodoTitle.vue'
import TodoInput from './components/TodoInput.vue'
import TodoList from "./components/TodoList.vue"
import TodoFooter from "./components/TodoFooter.vue"

export default {
  name: 'App',
  components: {
    TodoHeader,
    TodoTitle,
    TodoInput,
    TodoList,
    TodoFooter
  }
}
</script>

<style>

</style>
