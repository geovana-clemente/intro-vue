<template>
  <nav class="navbar">
    <ul class="nav-items">
      <slot></slot>
    </ul>
  </nav>
</template>

<style scoped>
.navbar {
  background: #e0aaff;
  padding: 1rem;
}
.nav-items {
  display: flex;
  gap: 1rem;
  list-style: none;
  padding: 0;
  margin: 0;
}
</style>