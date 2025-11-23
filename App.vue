<template>
  <h1>Gestor de Tareas</h1>
  <TaskList />
</template>

<script>
import TaskList from "./components/TaskList.vue";

export default {
  components: { TaskList }
};
</script>

<style>
body {
  font-family: Arial, sans-serif;
  padding: 20px;
}
</style>
