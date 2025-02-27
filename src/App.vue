<script setup lang="ts">
import MainHeader from './components/MainHeader.vue'
import TextInput from './components/TextInput.vue'
import TodoContainer from './components/TodoContainer.vue'
import FilterList from './components/FilterList.vue'
</script>

<template>
  <div class="container">
    <MainHeader />
    <main>
      <TextInput />
      <TodoContainer />
      <FilterList />
    </main>
    <footer>
      <p>Drag and drop to reorder list</p>
    </footer>
  </div>
</template>

<style scoped>
footer {
  text-align: center;
  color: hsla(235, 9%, 61%, 1);
  letter-spacing: -0.19px;
  font-size: 0.875rem;
}
</style>
