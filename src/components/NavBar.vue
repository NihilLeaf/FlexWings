<template>
  <div class="nav-container">
    <div class="section">
      <nav>
        <router-link :to="{ name: 'home' }">Home</router-link>
        <router-link :to="{ name: 'todo' }">Todo</router-link>
      </nav>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped lang="scss">
.nav-container {
  width: 100vw;
  height: 15vh;

  .section {
    padding-top: 7vh;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 12px;

    a {
      display: inline-block;
      text-decoration: none;
      outline: none;
      font-size: 28px;
      color: #77888c;

      &:hover {
        color: white;
        letter-spacing: 1px;
      }

      &:active {
        color: white;
      }
    }
  }
}
</style>
