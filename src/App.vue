<script setup lang="ts">
import MainHeader from './components/MainHeader.vue'
import TextInput from './components/TextInput.vue'
import TodoList from './components/TodoList.vue'
</script>

<template>
  <div class="container">
    <MainHeader />
    <main>
      <TextInput />
      <TodoList />
    </main>
  </div>
</template>

<style scoped></style>
