<template>
  <li>
    <div class="oval"></div>
    <div class="todo-item">
      <p>Todo item Lorem ipsum dolor sit amet consectetur.</p>
      <button type="button" aria-label="Delete todo item">
        <img src="../assets/images/icon-cross.svg" alt="Cross icon" />
      </button>
    </div>
  </li>
</template>

<style scoped>
li {
  --button-padding: 8px;
  height: 20px;
  padding-inline: 20px;
  display: flex;
  align-items: center;
  gap: 12px;
  font-size: 0.75rem;
}
.todo-item {
  width: 100%;
  display: flex;
  align-items: center;
  gap: 12px;
  justify-content: space-between;
  color: hsla(235, 19%, 35%, 1);
  letter-spacing: -0.17px;
}
.todo-item img {
  width: 12px;
  height: 12px;
}
.todo-item button {
  padding: var(--button-padding);
}
</style>
