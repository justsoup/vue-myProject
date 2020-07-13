<template>
    <div>
      <header class="header">
        <h1>todos</h1>
        <input
          type="text"
          class="new-todo"
          autofocus
          placeholder="请输入内容"
        >
      </header>
      <section class="main">
        <input
          type="checkbox"
          class="toggle-all"
        >
        <label for="toggle-all"></label>
        <ul class="todo-list">
          <li class="todo">
            <div class="view">
              <input type="checkbox" class="toggle">
              <label></label>
              <button class="destroy"></button>
            </div>
            <input type="text" class="edit">
          </li>
        </ul>
      </section>
      <footer class="footer">
        <span class="todo-count">
          <strong>111</strong>
        </span>
        <ul class="filters">
          <li>
            <a href="#/all">All</a>
          </li>
          <li>
            <a href="#/all">Active</a>
          </li>
          <li>
            <a href="#/all">Completed</a>
          </li>
        </ul>
        <button class="clear-completed">Clear completed</button>
      </footer>
    </div>
</template>

<script>
    export default {
        name: "todoContent"
    }
</script>

<style scoped>

</style>
