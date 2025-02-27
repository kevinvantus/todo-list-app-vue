<script setup lang="ts">
import TodoItem from './TodoItem.vue'
import TodoDivider from './TodoDivider.vue'
</script>

<template>
  <div class="todo-list">
    <TodoItem />
    <TodoDivider />
    <TodoItem />
    <TodoDivider />
    <TodoItem />
    <TodoDivider />
  </div>
</template>

<style scoped>
.todo-list {
  display: flex;
  flex-direction: column;
  gap: 16px;
}
</style>
