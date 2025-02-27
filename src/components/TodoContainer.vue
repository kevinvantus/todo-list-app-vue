<script setup lang="ts">
import TodoList from './TodoList.vue'
</script>

<template>
  <div class="todo-container">
    <TodoList />
    <footer>
      <span>5 items left</span>
      <button type="button">Clear Completed</button>
    </footer>
  </div>
</template>

<style scoped>
.todo-container {
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 0px 35px 50px -15px hsla(235, 19%, 80%, 0.5);
  padding-block-start: 16px;
}
.todo-container footer {
  padding: 16px 20px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.todo-container footer * {
  color: hsla(235, 9%, 61%, 1);
  font-size: 0.75rem;
  font-family: 'Josefin Sans', sans-serif;
}
</style>
