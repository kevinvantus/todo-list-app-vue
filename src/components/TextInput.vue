<template>
  <form class="text-container">
    <div class="oval"></div>

    <input type="text" placeholder="Create a new todo..." />
  </form>
</template>

<style scoped>
form {
  padding-inline: 20px;
  height: 48px;
  box-shadow: 0px 35px 50px -15px #c2c3d680;
  background-color: #fff;
  border-radius: 5px;
  display: flex;
  align-items: center;
  gap: 12px;
}

input {
  width: 100%;
  height: 100%;
  font-size: 0.75rem;
  border: none;
  outline: none;
  color: hsla(235, 14%, 26%, 1);
  caret-color: var(--bright-blue);
  font-family: Josefin Sans;
  line-height: 0.75;
  letter-spacing: -0.17px;
}

::placeholder {
  color: hsla(235, 9%, 61%, 1);
}
</style>
