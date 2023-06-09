<template>
  <div class="todo">
    <h2>Afazeres:</h2>
    <div class="todo-container">
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Todo-List",
};
</script>

<style scoped lang="scss">
.todo {
  h2 {
    margin-top: 2rem;
    text-align: center;
  }

  .todo-container {
    width: 80vw;
    margin: 0 auto;
    display: grid;
    grid-column: 7;
    grid-template-columns: 1fr;
  }
}
</style>
