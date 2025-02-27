<template>
  <div class="todo-item">
    <div class="oval"></div>
    <div class="todo-text">
      <p>Todo item Lorem ipsum dolor sit amet consectetur.</p>
      <button type="button" aria-label="Delete todo item">
        <img src="../assets/images/icon-cross.svg" alt="Cross icon" />
      </button>
    </div>
  </div>
</template>

<style scoped>
.todo-item {
  --button-padding: 8px;
  height: 20px;
  padding-inline: 20px;
  display: flex;
  align-items: center;
  gap: 12px;
  font-size: 0.75rem;
}
.todo-text {
  width: 100%;
  height: 20px;
  display: flex;
  align-items: center;
  gap: 12px;
  justify-content: space-between;
  color: hsla(235, 19%, 35%, 1);
  letter-spacing: -0.17px;
}
.todo-text img {
  width: 12px;
  height: 12px;
}
.todo-text button {
  padding: var(--button-padding);
}
</style>
