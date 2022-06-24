<template>
  <div id="app">
    <div class="container">
      <AddToDo/>
      <FilterTodos/>
      <ToDos/>
    </div>
  </div>
</template>

<script>
import ToDos from "./components/Todos.vue";
import AddToDo from "./components/AddToDo.vue"
import FilterTodos from "./components/FilterTodos.vue";

export default {
  name: "app",
  components: {
    ToDos,
    AddToDo,
    FilterTodos 
  }
};
</script>

<style>
body {
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height: 1.6;
  background: #e8f7f0;
}
.container {
  max-width: 1100px;
  margin: auto;
  overflow: auto;
  padding: 0 2rem;
}
</style>