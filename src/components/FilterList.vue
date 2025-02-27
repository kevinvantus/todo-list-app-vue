<template>
  <div class="filter-list">
    <label>
      All
      <input type="radio" name="filter" />
    </label>
    <label>
      Active
      <input type="radio" name="filter" />
    </label>
    <label>
      Completed
      <input type="radio" name="filter" />
    </label>
  </div>
</template>

<style scoped>
.filter-list {
  height: 48px;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 18px;
  background-color: #fff;
  box-shadow: 0px 35px 50px -15px hsla(235, 19%, 80%, 0.5);
  border-radius: 5px;
  font-size: 0.875rem;
  font-weight: 700;
  letter-spacing: -0.19px;
}
.filter-list input {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border: 0;
}
.filter-list label {
  cursor: pointer;
}
.filter-list label:has(:checked) {
  color: var(--bright-blue);
}
</style>
